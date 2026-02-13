# ¿Dónde Están los Muertos?

### Sustitución Estadística de la Violencia en México (2015–2025)

> Análisis exploratorio que contrasta homicidios dolosos reportados por fiscalías (SESNSP) contra defunciones certificadas (INEGI), muertes de clasificación ambigua y personas desaparecidas (CNB). La hipótesis central es que la reducción en homicidios dolosos no refleja menos violencia, sino una redistribución entre categorías estadísticas.

🔴 **Ver visualización en vivo →** [araujome.github.io/visualizaciones/donde-estan-los-muertos/](https://araujome.github.io/visualizaciones/donde-estan-los-muertos/)
---

## ⚠️ Nota Importante

**Esta es una pieza de análisis exploratorio, no una investigación peer-reviewed.** Dos de las cuatro series de datos son estimaciones derivadas por el autor (ver Metodología de Datos). Se presentan explicaciones alternativas a la hipótesis principal dentro de la propia visualización.

---

## Descripción

El dashboard compara cuatro series temporales (2015–2025) para evidenciar correlaciones anómalas entre la reducción reportada en homicidios dolosos y el aumento simultáneo en categorías adyacentes:

| Capa visual | Serie | Fuente |
|---|---|---|
| 🔴 Área roja | Homicidios dolosos + feminicidio | SESNSP (Carpetas) |
| 🟡 Área ámbar | Clasificación ambigua (culposos + indeterminados) | SESNSP + INEGI (Derivada) |
| ⬜ Área gris | Personas desaparecidas (flujo anual) | CNB/RNPDNO (Derivada) |
| ⚪ Línea punteada | Defunciones por homicidio certificadas | INEGI (Control) |

### Hallazgos clave

1. **Divergencia Institucional:** La línea INEGI (cuerpos certificados) y el área SESNSP (carpetas) se separan progresivamente a partir de 2019, indicando miles de muertes violentas que no se investigan como homicidios dolosos.

2. **Desplazamiento entre Categorías:** El aumento combinado en muertes de clasificación ambigua y desapariciones (~13,700 casos) supera la reducción reportada en homicidios dolosos (~9,100 casos entre 2019 y 2025*).

3. **Meseta de Violencia:** Pese a la reducción oficial en la categoría roja, el volumen total apilado se mantiene por encima de 70,000 registros anuales.

---

## Metodología de Datos

### Series verificables (Datos oficiales directos)

**Serie 1 — Homicidios Dolosos + Feminicidio**

- **Fuente:** SESNSP — Incidencia Delictiva del Fuero Común
- **URL:** [gob.mx/sesnsp — Datos Abiertos](https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva)
- **Período verificado:** 2015–2023
- **2024:** Estimación con datos enero–septiembre anualizados
- **2025:** Proyección lineal basada en tendencia 2022–2024

**Serie 2 — Defunciones por Homicidio (INEGI)**

- **Fuente:** INEGI — Estadísticas de Defunciones Registradas
- **URL:** [inegi.org.mx/programas/mortalidad](https://www.inegi.org.mx/programas/mortalidad/)
- **Período verificado:** 2015–2022 (último año publicado: octubre 2023)
- **2023–2025:** Estimación del autor basada en tendencia histórica + datos preliminares SESNSP
- **Nota:** INEGI reporta históricamente ~8–15% más homicidios que SESNSP

### Series derivadas (Estimaciones del autor)

**Serie 3 — Clasificación Ambigua**

- **Composición:** Homicidios culposos (SESNSP) + Muertes con causa indeterminada (INEGI)
- **Método:** Suma de ambas subcategorías, redondeada al millar más cercano
- **Limitación conocida:** Los homicidios culposos incluyen siniestros viales genuinos y muertes naturales mal clasificadas. Esto puede inflar artificialmente la serie
- **⚠️ Los valores redondeados indican estimación, no datos oficiales directos**

**Serie 4 — Personas Desaparecidas (flujo anual)**

- **Fuente base:** CNB — Registro Nacional de Personas Desaparecidas y No Localizadas (RNPDNO)
- **URL:** [Plataforma CNB](https://vfrfrp-plataforma.segob.gob.mx/)
- **Método:** Delta interanual del acumulado (~115,000 personas al 2024), ajustado por fecha de último avistamiento
- **Limitación conocida:** El fortalecimiento del RNPDNO a partir de 2018 aumenta la capacidad de registro sin que necesariamente aumenten los casos reales. Esto puede inflar la tendencia ascendente
- **⚠️ Valores derivados del acumulado CNB por el autor**

### Proyecciones 2024–2025

- **2024:** Datos enero–septiembre anualizados (SESNSP) + tendencia INEGI
- **2025:** Proyección lineal basada en tendencia 2022–2024
- **Sin intervalos de confianza** — tratar como indicativos, no predictivos
- La visualización marca estos años con una zona de proyección diferenciada visualmente
---

## Explicaciones Alternativas

Este análisis plantea una hipótesis de sustitución estadística. En rigor investigativo, deben considerarse explicaciones alternativas:

| Alternativa | Descripción |
|---|---|
| **Mejora en registro** | El RNPDNO se fortaleció significativamente en 2018–2020. El aumento en desapariciones registradas puede reflejar mayor capacidad de denuncia, no necesariamente más casos reales |
| **Cambios en protocolos forenses** | La actualización de protocolos de certificación de defunciones puede reclasificar muertes por criterios técnicos, sin intención de ocultamiento |
| **Siniestros viales** | La categoría "homicidio culposo" incluye muertes por accidentes de tránsito, cuya dinámica es independiente de la violencia criminal |
| **Factores demográficos** | Cambios en la estructura poblacional de la cohorte 18–35 (principal víctima de homicidio) podrían explicar parte de la reducción |

---

## Tecnologías

| Componente | Tecnología |
|---|---|
| Gráficas | Chart.js 4.x |
| Plugins | chartjs-plugin-datalabels 2.2, chartjs-plugin-annotation 3.0 |
| Estilos | Tailwind CSS (CDN) |
| Tipografía | Inter (Google Fonts) |
| Iconos | Font Awesome 6.5 |
| Captura de imagen | html2canvas |
| Despliegue | GitHub Pages (archivo HTML estático) |

### Arquitectura

        Artefacto single-file HTML. Todas las dependencias se cargan por CDN. No requiere build step ni servidor.
                    visualizaciones/
            ├── donde-estan-los-muertos.html   ← Visualización principal
            ├── assets/
            │   └── preview_violencia.png      ← Imagen para Open Graph
            └── README.md                      ← Este archivo

---

## Cómo usar

**Ver en línea:** Visita [araujome.github.io/visualizaciones/donde-estan-los-muertos/](https://araujome.github.io/visualizaciones/donde-estan-los-muertos/)
**Guardar como imagen:** Haz clic en el botón 📷 Guardar Imagen en la esquina superior derecha del dashboard. Se descargará un PNG en alta resolución (2x).

**Clonar y modificar:**

```bash
git clone https://github.com/AraujoME/visualizaciones.git
cd visualizaciones
# Abrir donde-estan-los-muertos.html en cualquier navegador

**BLOQUE 3** — Pegar inmediatamente después del bloque 2:

```text
---

## Evolución del proyecto

Esta visualización pasó por 5 iteraciones documentadas con revisión técnica en data storytelling, UX/UI, heurísticas de Nielsen, rigor estadístico, ética de datos, programación y accesibilidad.

| Versión | Cambios principales | Nota |
|---|---|:---:|
| V1 | Diseño original, gráfica de áreas apiladas | 5.4 |
| V2 | Corrección de KPI, meta tags, accesibilidad básica | 6.0 |
| V3 | Eje Y2 para INEGI, zona de proyección, terminología unificada | 7.0 |
| V4 | Explicaciones alternativas, documentación de datos en código | 7.8 |
| **V5** | **Claves de lectura ampliadas, subjuntivo en hipótesis, tooltip corregido, enlace a repo en descargo** | **8.0** |

---

## Licencias

| Alcance | Licencia |
|---|---|
| **Contenido** (textos, análisis, diseño visual) | [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) |
| **Código** (HTML, JavaScript, configuración Chart.js) | [MIT](https://opensource.org/licenses/MIT) |

Puedes reutilizar, adaptar y redistribuir el código libremente. El contenido analítico requiere atribución y no permite uso comercial.

---

## Autor

**Eric Araujo Martínez**

- 🐦 Twitter/X: [@SocioNomicsLab](https://x.com/SocioNomicsLab)
- 💼 LinkedIn: [ericaraujom](https://www.linkedin.com/in/ericaraujom/)
- 💻 GitHub: [AraujoME](https://github.com/AraujoME/visualizaciones)

---

## Citar este trabajo
Araujo Martínez, E. (2025). ¿Dónde están los muertos? Sustitución estadística 
de la violencia en México (2015–2025). SocioNomics Lab. 
https://araujome.github.io/visualizaciones/donde-estan-los-muertos/
