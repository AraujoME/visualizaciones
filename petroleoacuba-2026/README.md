# 🛢️ Diplomacia del Crudo  
## Auditoría México–Cuba (2019–2026)

![Code License](https://img.shields.io/badge/Code-MIT-green)
![Data License](https://img.shields.io/badge/Data-CC%20BY--NC%204.0-orange)
![Status](https://img.shields.io/badge/Status-PAUSADO%20(2026)-red)

Auditoría visual de inteligencia financiera sobre el flujo energético entre México y Cuba.  
Un ejercicio de **periodismo de datos** basado en fuentes abiertas para analizar el **costo de oportunidad**, la **opacidad financiera** y el **impacto geopolítico** de los envíos de crudo no cobrados.

👉 **Ver estudio interactivo:**  
https://araujome.github.io/visualizaciones/petroleoacuba-2026/

---

## 📋 Descripción del Proyecto

Este proyecto visualiza la evolución de los envíos de petróleo de Pemex a Cuba desde el inicio de la administración de Andrés Manuel López Obrador (2019) hasta la *pausa técnica* anunciada bajo el gobierno de Claudia Sheinbaum (enero de 2026).

La herramienta permite dimensionar el **costo fiscal implícito** de estos envíos mediante comparativas tangibles (infraestructura hospitalaria) y señala **posibles discrepancias de valoración** entre reportes financieros internacionales y estimaciones basadas en registros aduanales y tráfico marítimo.

---

## 🎯 Objetivos de la Visualización

- Auditar el volumen estimado de barriles enviados frente a la opacidad en el desglose oficial.
- Traducir el impacto financiero a términos de gasto social (Salud vs. Diplomacia).
- Señalar la brecha de valoración aproximada (~$2,600 M USD) entre ingresos reportados y valor de mercado estimado.

---

## 🔍 Hallazgos Clave (Intelligence Brief)

| Indicador | Dato | Contexto |
|---------|------|---------|
| Valor total estimado | ~$3,000 M USD | Acumulado sexenal (2019–2024) |
| Pico histórico | Octubre 2024 | 845,000 barriles enviados en un solo mes |
| Costo de oportunidad | $12,100 MDP | Equivalente a ~6 Hospitales Generales IMSS |
| Estatus actual | 🔴 PAUSADO | Envíos detenidos en enero 2026 |

---

## 🛠️ Metodología y Fuentes de Datos

Este reporte se construye mediante **triangulación de fuentes abiertas (OSINT)**, reportes financieros oficiales e investigaciones periodísticas.

### Fuentes de inteligencia

- **Pemex – Relación con Inversionistas**  
  Reportes financieros y Form 20-F presentados ante la SEC de EE.UU.  
  https://www.pemex.com/ri

- **Mexicanos Contra la Corrupción (MCCI) / Reuters**  
  Investigaciones periodísticas y rastreo de buques tanque mediante datos públicos y satelitales.  
  https://contralacorrupcion.mx  
  https://www.reuters.com

- **SHCP – Transparencia Presupuestaria**  
  Costos paramétricos de infraestructura hospitalaria (Cartera de Inversión del PPEF).  
  https://www.transparenciapresupuestaria.gob.mx

### Nota técnica sobre los datos

- **2019–2022:** Los datos mensuales son interpolaciones derivadas de estimaciones anuales agregadas.
- **2023–2026:** Datos basados en reportes mensuales específicos de tráfico marítimo.
- **Valoración:** Se utiliza el precio promedio del WTI como referencia estándar de costo de oportunidad para exportaciones de crudo en la región.

Las cifras presentadas están sujetas a variación según metodología y fuente.

---

## 💻 Stack Tecnológico

- **Estructura:** HTML5 semántico  
- **Estilos:** Tailwind CSS (vía CDN)  
- **Visualización:** Chart.js + chartjs-plugin-annotation  
- **Exportación:** html2canvas (PNG alta resolución)  
- **Tipografía:** Inter (UI) y JetBrains Mono (datos)

---

## 🚀 Instalación y Uso

No requiere instalación de dependencias. Proyecto *client-side* puro.

```bash
git clone https://github.com/AraujoME/visualizaciones.git

---

## 👤 Autor

**Eric Araujo Martínez**  
Director — **SocioNomics Lab**

- 🌐 **X (Twitter):** https://x.com/SocioNomicsLab  
- 💼 **LinkedIn:** https://www.linkedin.com/in/ericaraujo/  
- 💻 **GitHub:** https://github.com/AraujoME  

---

## ⚖️ Licencia

Este proyecto utiliza **licenciamiento dual**:

- **Contenido visual y datos:**  
  Creative Commons **CC BY-NC 4.0**  
  *(Atribución requerida · Uso no comercial)*

- **Código fuente:**  
  **MIT License**  
  *(Uso libre, incluyendo fines comerciales)*

> Para usos comerciales del contenido visual o de los datos, se requiere autorización explícita del autor.

---

## ⚠️ Descargo de Responsabilidad

> Este proyecto es un ejercicio de **periodismo de datos** y **análisis de política pública**, basado en **estimaciones** y **fuentes abiertas**.
>
> No constituye una auditoría oficial, legal ni contable.
>
> Las cifras presentadas representan **valores de mercado estimados** y pueden diferir de los registros contables internos de las entidades mencionadas.
>
> El contenido se proporciona con fines **informativos y analíticos**, no como evidencia legal.
