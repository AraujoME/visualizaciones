# 🌎 Monitor de Riesgo Soberano | América Latina

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc/4.0/)
[![Code License: MIT](https://img.shields.io/badge/Code-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://araujome.github.io/visualizaciones/riesgo-pais/)

> **Dashboard interactivo de Riesgo País (EMBI)** para 6 países de América Latina con estética "terminal financiero" y exportación HTML/PDF.

![Preview](preview.png)

---

## 🎯 ¿Qué es este proyecto?

Monitor visual que rastrea la evolución del **EMBI (Emerging Markets Bond Index)** desde 2013 hasta proyecciones 2026 para:

- 🇲🇽 México
- 🇨🇴 Colombia
- 🇨🇷 Costa Rica
- 🇵🇦 Panamá
- 🇦🇷 Argentina
- 🇻🇪 Venezuela

El EMBI mide el **riesgo soberano**: la "sobretasa" que un país paga por endeudarse vs. bonos del Tesoro de EE.UU. (considerados libres de riesgo).

**Interpretación simple:**
- ⬆️ **EMBI alto** = Mercados desconfían → Crédito más caro para gobierno, empresas y ciudadanos
- ⬇️ **EMBI bajo** = Mercados confían → Crédito accesible, inversión extranjera

---

## ✨ Características

### 🎨 **Diseño**
- Estética **"Terminal Financiero"** (fondos oscuros + tipografía monoespaciada)
- Ticker animado superior con datos en tiempo real
- Paleta de colores diferenciada por país (+ accesibilidad para daltónicos)
- Responsive completo (mobile-first)

### 📊 **Funcionalidad**
- Gráfica interactiva con Chart.js
- Venezuela oculto por defecto (no rompe escala)
- Anotación contextual: "Cambios de Gobierno (MX/CO)"
- Tooltips informativos con datos formateados

### ♿ **Accesibilidad**
- ARIA labels completos
- Focus states para navegación por teclado
- `prefers-reduced-motion` para desactivar animaciones
- Diferenciación no cromática (líneas punteadas)

### 💾 **Exportación**
- **Descargar HTML:** Archivo autocontenido interactivo
- **Exportar PDF:** Alta resolución (scale: 3) para reportes

---

## 🚀 Demo en Vivo

👉 **[Ver Dashboard](https://araujome.github.io/visualizaciones/riesgo-pais/)**

---

## 📂 Estructura del Proyecto

```
riesgo-pais/
├── index.html              # Dashboard principal (autocontenido)
├── README.md               # Este archivo
├── preview.png             # Screenshot del dashboard
└── data/
    └── embi_datos.xlsx     # Fuentes y metodología
```

---

## 📊 Datos y Fuentes

### ⚠️ **Transparencia de Datos (IMPORTANTE)**

Los valores del EMBI son **aproximaciones** derivadas de:

1. **Artículos académicos** (2000-2019): [Scielo UNAM](https://www.scielo.org.mx/)
2. **Análisis históricos** (2013-2019): [MéxicoMéxico.org](http://www.mexicomaxico.org/Voto/Riesgo.htm)
3. **Prensa especializada** (2024-2025): Bloomberg Línea, Reuters
4. **Proyecciones** (2025-2026): Consenso de mercado + estimación propia

**Estos NO son datos oficiales de J.P. Morgan.**

Para datos precisos en tiempo real, se requiere suscripción a:
- J.P. Morgan Markets
- Bloomberg Terminal
- Refinitiv Eikon

### 📋 Hoja de Cálculo Completa

📊 **[Ver datos completos con fuentes](https://docs.google.com/spreadsheets/d/1YoL1FadcMW9lCabS4SLVieNxv_Yn1FG3/edit?usp=sharing)**

Incluye:
- Tabla histórica (2013-2026)
- Fuentes por periodo
- Notas metodológicas
- Contexto geopolítico

---

## 🛠️ Stack Técnico

| Tecnología | Uso |
|------------|-----|
| **Chart.js** | Gráfica de líneas interactiva |
| **Tailwind CSS** | Sistema de diseño (CDN) |
| **html2canvas** | Captura para PDF |
| **jsPDF** | Generación de PDFs |
| **Font Awesome** | Iconografía |
| **Inter + JetBrains Mono** | Tipografía (Google Fonts) |

**No requiere build process.** Todo funciona desde el HTML.

---

## 💻 Uso Local

### Opción 1: Abrir directamente
```bash
# Clona el repositorio
git clone https://github.com/araujome/visualizaciones.git

# Navega al proyecto
cd visualizaciones/riesgo-pais/

# Abre index.html en tu navegador
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Opción 2: Servidor local (recomendado)
```bash
# Python 3
python -m http.server 8000

# Luego abre: http://localhost:8000
```

---

## 🎓 Uso Educativo y Académico

### ✅ **Permitido**
- Usar en clases de economía, finanzas o ciencia de datos
- Citar en papers académicos (ver sección de citas)
- Adaptar código para proyectos educativos
- Republicar con atribución (ver licencia)

### ❌ **No Permitido**
- Uso comercial sin autorización
- Presentar como datos oficiales de J.P. Morgan
- Remover disclaimers de limitaciones metodológicas

---

## 📖 Cómo Citar

### APA 7
```
Araujo Martínez, E. (2025). Monitor de Riesgo Soberano: América Latina 
(2013-2026) [Dashboard interactivo]. SocioNomics Lab. 
https://araujome.github.io/visualizaciones/riesgo-pais/
```

### BibTeX
```bibtex
@misc{araujo2025embi,
  author = {Araujo Martínez, Eric},
  title = {Monitor de Riesgo Soberano: América Latina (2013-2026)},
  year = {2025},
  howpublished = {\url{https://araujome.github.io/visualizaciones/riesgo-pais/}},
  note = {Dashboard interactivo. SocioNomics Lab}
}
```

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. **Fork** el repositorio
2. Crea una **rama** (`git checkout -b feature/mejora`)
3. **Commit** tus cambios (`git commit -m 'Add: nueva feature'`)
4. **Push** a la rama (`git push origin feature/mejora`)
5. Abre un **Pull Request**

### Áreas de mejora identificadas
- [ ] Agregar más países (Brasil, Chile, Perú)
- [ ] Modo comparativo (seleccionar N países)
- [ ] Datos en tiempo real (API de Yahoo Finance)
- [ ] Exportación a Excel/CSV
- [ ] Análisis de correlación entre países

---

## 📜 Licencias

### Contenido
[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)

El contenido (datos, análisis, diseño visual) está bajo [Creative Commons Attribution-NonCommercial 4.0](http://creativecommons.org/licenses/by-nc/4.0/).

**Resumen:**
- ✅ Compartir y adaptar con atribución
- ❌ Uso comercial (requiere permiso)

### Código
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

El código fuente está bajo [MIT License](https://opensource.org/licenses/MIT).

**Resumen:**
- ✅ Uso, copia, modificación y distribución libre
- ✅ Incluso para fines comerciales
- ⚠️ Sin garantía de funcionamiento

---

## 🔗 Links

| Recurso | Link |
|---------|------|
| **Portfolio Completo** | [araujome.github.io/visualizaciones](https://araujome.github.io/visualizaciones/) |
| **Datos (Google Sheets)** | [Ver hoja de cálculo](https://docs.google.com/spreadsheets/d/1YoL1FadcMW9lCabS4SLVieNxv_Yn1FG3/edit?usp=sharing) |
| **Demo en Vivo** | [Dashboard EMBI](https://araujome.github.io/visualizaciones/riesgo-pais/) |
| **Repositorio** | [github.com/araujome/visualizaciones](https://github.com/araujome/visualizaciones) |

---

## 👤 Autor

**Eric Araujo Martínez**  
Economista | Abogado | MBA

- 🌐 Portfolio: [araujome.github.io/visualizaciones](https://araujome.github.io/visualizaciones/)
- 💼 LinkedIn: [linkedin.com/in/ericaraujom](https://www.linkedin.com/in/ericaraujom/)
- 🐦 Twitter: [@SocioNomicsLab](https://x.com/SocioNomicsLab)
- 📧 Email: Disponible en perfil de GitHub

---

## ⚠️ Disclaimer Legal

**EMBI y J.P. Morgan** son marcas registradas de JPMorgan Chase & Co. 

Este proyecto es una visualización de datos **independiente** sin afiliación comercial. Los datos presentados son aproximaciones de fuentes secundarias (académicas y periodísticas) y **NO constituyen datos oficiales** de J.P. Morgan.

Para obtener datos precisos en tiempo real, se requiere suscripción institucional a:
- J.P. Morgan Markets
- Bloomberg Terminal
- Refinitiv Eikon

**Uso del Dashboard:**  
Este proyecto se ofrece "tal cual" sin garantías de exactitud. No debe usarse como base única para decisiones de inversión. Consulte fuentes oficiales y asesores financieros profesionales antes de tomar decisiones financieras.

---

## 📊 Estadísticas del Proyecto

![GitHub repo size](https://img.shields.io/github/repo-size/araujome/visualizaciones)
![GitHub last commit](https://img.shields.io/github/last-commit/araujome/visualizaciones)
![GitHub stars](https://img.shields.io/github/stars/araujome/visualizaciones?style=social)

---

## 🙏 Agradecimientos

- **J.P. Morgan** por la metodología EMBI (fuente conceptual)
- **Chart.js** por la librería de gráficas
- **Tailwind CSS** por el sistema de diseño
- **Comunidad académica** que publica datos históricos abiertos
- **Lectores y usuarios** que reportan errores y sugieren mejoras

---

<div align="center">

**Hecho con 📊 y ☕ en México**

[⬆️ Volver arriba](#-monitor-de-riesgo-soberano--américa-latina)

</div>
