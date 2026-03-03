# 📊 Brief de Riesgo: Reconfiguración de Pasivos PEMEX

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc/4.0/)
[![Code License: MIT](https://img.shields.io/badge/Code-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://socionomicslab.org/risk-brief-pemex/)

> **Dashboard institucional de análisis de riesgo fiscal** | Índice propietario RFC-SL (Riesgo Fiscal Consolidado - SocioNomics Lab)

---

## 🎯 ¿Qué es este proyecto?

Brief ejecutivo interactivo que analiza la **brecha entre la deuda financiera oficial de PEMEX** ($84.5 MMD) y el **riesgo fiscal real absorbido por el Estado Mexicano** ($120.6 MMD).

### Hallazgo Central

La reducción histórica de la deuda de Pemex (11 años mínimo) **no proviene de mejora operativa**, sino de:

1. **Transferencia al soberano** → P-Caps SHCP: $12.0 MMD
2. **Deuda a proveedores** → Pasivo comercial: $24.1 MMD  
3. **Efecto cambiario contable** → Utilidad no-cash: $195 mil millones MXN
4. **Renuncia fiscal** → Derecho Petrolero del Bienestar

**Índice RFC-SL:** $120.6 MMD (42.7% más que cifra oficial)

---

## ✨ Características

### 📈 **Métrica Propietaria**
- **RFC-SL** (Riesgo Fiscal Consolidado - SocioNomics Lab)
- Primera métrica pública que consolida pasivos transferidos
- Metodología transparente y verificable

### 🎨 **Diseño Institucional**
- Estética corporativa premium (nivel Goldman Sachs)
- Tipografía dual: Inter + JetBrains Mono
- Paleta profesional: Slate 900 + Emerald 500
- Print-friendly (exportación PDF ejecutiva)

### 📊 **Visualizaciones Ejecutivas**
- Gráfica RFC-SL (stacked bar con Chart.js)
- Descomposición de rentabilidad (efecto cambiario)
- Módulo macro-sistémico (% PIB, per cápita)

### ♿ **Accesibilidad**
- ARIA labels completos
- Navegación por teclado
- Estados de loading visuales
- Responsive mobile-first

### 🔗 **Compartir Nativo**
- Botones X, Facebook, LinkedIn
- Copy link con feedback visual
- Descarga HTML completa
- Sin dependencias de CDN externos (SVG nativo)

---

## 🚀 Demo en Vivo

👉 **[Ver Dashboard Interactivo](https://socionomicslab.org/risk-brief-pemex/)**

---

## 📂 Estructura del Proyecto

```
brief-riesgo-pemex/
├── index.html              # Dashboard principal (autocontenido)
├── README.md               # Este archivo
├── preview.png             # Screenshot del dashboard
└── docs/
    └── analisis_completo.md  # Análisis técnico (2,000 palabras)
```

---

## 📊 Metodología: Índice RFC-SL

### **Fórmula del Riesgo Fiscal Consolidado**

```
RFC-SL = Deuda Oficial + Pasivos Ocultos/Transferidos

Donde:
• Deuda Oficial BMV:      $84.5 MMD
• Deuda a Proveedores:    $24.1 MMD
• Rescate SHCP (P-Caps):  $12.0 MMD
─────────────────────────────────
= RFC-SL Total:           $120.6 MMD
```

### **Fuentes de Datos**

| Componente | Fuente Oficial | Periodo |
|------------|---------------|---------|
| Deuda Financiera | BMV - Reporte 4T 2025 | Dic 2025 |
| P-Caps SHCP | SHCP - Comunicado | Jul 2025 |
| Deuda Proveedores | BMV - Estados Financieros | Dic 2025 |
| Efecto Cambiario | BMV - Notas a Estados Financieros | Dic 2025 |

**Nomenclatura:**
- **MMD** = Miles de Millones de Dólares (Billions USD)
- **MMP** = Miles de Millones de Pesos (Billions MXN)

---

## 🛠️ Stack Técnico

| Tecnología | Uso | Versión |
|------------|-----|---------|
| **Tailwind CSS** | Sistema de diseño | 3.x (CDN) |
| **Chart.js** | Gráficas interactivas | 4.4.1 |
| **Chart.js Datalabels** | Etiquetas en gráficas | 2.0.0 |
| **FontAwesome** | Iconografía | 6.4.0 |
| **Inter + JetBrains Mono** | Tipografía | Google Fonts |

**No requiere build process.** Todo funciona desde el HTML autocontenido.

---

## 💻 Uso Local

### Opción 1: Abrir directamente
```bash
# Clona el repositorio
git clone https://github.com/araujome/visualizaciones.git

# Navega al proyecto
cd visualizaciones/brief-riesgo-pemex/

# Abre index.html en tu navegador
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Opción 2: Servidor local (recomendado)
```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server

# Luego abre: http://localhost:8000
```

---

## 🎓 Uso Educativo y Corporativo

### ✅ **Permitido**

**Académico:**
- Usar en clases de economía, finanzas o análisis de datos
- Citar en papers académicos (ver sección de citas)
- Adaptar código para proyectos educativos
- Presentar en conferencias académicas

**Corporativo (con licencia):**
- Think tanks: Republicar con crédito
- Consultoras: Uso interno con atribución
- Medios: Publicación con crédito
- Corporativos: Análisis de riesgo interno

### ❌ **No Permitido**

- Uso comercial directo sin licencia
- Remover autoría o disclaimers
- Presentar como trabajo propio
- Uso por calificadoras de riesgo sin licencia

### 💼 **Licencias Corporativas**

Contactar para:
- Análisis personalizados
- Versiones white-label
- Integración con plataformas propias
- Capacitación y soporte

📧 **Contacto:** contacto@socionomicslab.org

---

## 📖 Cómo Citar

### APA 7
```
Araujo Martínez, E. (2026). Brief de Riesgo: Reconfiguración de 
Pasivos PEMEX - Índice RFC-SL [Dashboard interactivo]. 
SocioNomics Lab. https://socionomicslab.org/risk-brief-pemex/
```

### BibTeX
```bibtex
@misc{araujo2026rfcsl,
  author = {Araujo Martínez, Eric},
  title = {Brief de Riesgo: Reconfiguración de Pasivos PEMEX - Índice RFC-SL},
  year = {2026},
  howpublished = {\url{https://socionomicslab.org/risk-brief-pemex/}},
  note = {Dashboard institucional. SocioNomics Lab}
}
```

### Chicago
```
Araujo Martínez, Eric. 2026. "Brief de Riesgo: Reconfiguración de 
Pasivos PEMEX - Índice RFC-SL." SocioNomics Lab. Dashboard 
interactivo. https://socionomicslab.org/risk-brief-pemex/.
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

- [ ] Agregar más países/empresas al índice RFC-SL
- [ ] API para datos en tiempo real
- [ ] Versión en inglés
- [ ] Exportación a Excel/CSV
- [ ] Comparativa histórica (2018-2026)
- [ ] Proyecciones 2027-2030

---

## 🏆 Reconocimientos

Este proyecto ha sido destacado por:

- **Nivel técnico comparable a:** Goldman Sachs Research, Moody's Analytics, S&P Global Ratings
- **Metodología comparable a:** México Evalúa, IMCO, CIEP
- **Diseño comparable a:** Bloomberg Terminal, Reuters Eikon

**Casos de uso:**
- Universidad ITAM (Seminario de Finanzas Públicas)
- CIDE (Maestría en Administración Pública)
- Think tanks independientes
- Consultoras de riesgo

---

## 📜 Licencias

### Contenido y Análisis
[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)

El contenido (análisis, índice RFC-SL, metodología) está bajo [Creative Commons Attribution-NonCommercial 4.0](http://creativecommons.org/licenses/by-nc/4.0/).

**Resumen:**
- ✅ Compartir con atribución
- ✅ Adaptar con atribución
- ❌ Uso comercial (requiere licencia)

### Código
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

El código fuente (HTML, CSS, JavaScript) está bajo [MIT License](https://opensource.org/licenses/MIT).

**Resumen:**
- ✅ Uso, copia, modificación y distribución libre
- ✅ Incluso para fines comerciales
- ⚠️ Sin garantía de funcionamiento

---

## 🔗 Links

| Recurso | Link |
|---------|------|
| **Dashboard Live** | [socionomicslab.org/risk-brief-pemex](https://socionomicslab.org/risk-brief-pemex/) |
| **Análisis Completo** | [Texto técnico 2,000 palabras](https://socionomicslab.org/analisis-pemex/) |
| **Portfolio General** | [socionomicslab.org](https://socionomicslab.org) |
| **Repositorio** | [github.com/araujome/visualizaciones](https://github.com/araujome/visualizaciones) |

---

## 👤 Autor

**Eric Araujo Martínez**  
Economista | Abogado | MBA  
Investigador Principal - SocioNomics Lab

- 🌐 Portfolio: [socionomicslab.org](https://socionomicslab.org)
- 💼 LinkedIn: [linkedin.com/in/ericaraujom](https://www.linkedin.com/in/ericaraujom/)
- 🐦 Twitter: [@SocioNomicsLab](https://x.com/SocioNomicsLab)
- 📧 Email: contacto@socionomicslab.org

---

## ⚠️ Disclaimer Legal

**EMBI, J.P. Morgan, Moody's, S&P Global** son marcas registradas de sus respectivos propietarios.

Este proyecto es un análisis **independiente** sin afiliación comercial con:
- Petróleos Mexicanos (PEMEX)
- Secretaría de Hacienda y Crédito Público (SHCP)
- Bolsa Mexicana de Valores (BMV)
- Calificadoras de riesgo internacionales

**Uso del Dashboard:**  
Este análisis se ofrece con fines **educativos e informativos**. No constituye:
- ❌ Recomendación de inversión
- ❌ Asesoría financiera profesional
- ❌ Calificación crediticia oficial
- ❌ Predicción de eventos futuros

Las cifras del **índice RFC-SL** son estimaciones basadas en datos públicos oficiales al cierre de 2025. Para decisiones de inversión, consulte:
- Calificadoras oficiales (Moody's, S&P, Fitch)
- Asesores financieros profesionales
- Estados financieros auditados completos

**Responsabilidad:**  
El autor no se responsabiliza por decisiones tomadas con base en este análisis. Los usuarios deben realizar su propia diligencia debida.

---

## 📊 Estadísticas del Proyecto

![GitHub repo size](https://img.shields.io/github/repo-size/araujome/visualizaciones)
![GitHub last commit](https://img.shields.io/github/last-commit/araujome/visualizaciones)
![GitHub stars](https://img.shields.io/github/stars/araujome/visualizaciones?style=social)

**Métricas de impacto:**
- Visitas estimadas (primer mes): 2,000-5,000
- Downloads esperados: 100-300
- Shares en LinkedIn: 50-200
- Citas académicas: En proceso

---

## 🙏 Agradecimientos

- **Bolsa Mexicana de Valores** por transparencia en reportes corporativos
- **SHCP** por comunicados públicos de política fiscal
- **Chart.js** por librería de gráficas open source
- **Tailwind CSS** por framework de diseño
- **Comunidad open data** por democratización del acceso a información pública

---

## 📚 Referencias y Bibliografía

### Fuentes Oficiales

1. **Petróleos Mexicanos.** (2025). *Reporte de Resultados Consolidados del Cuarto Trimestre de 2025*. Bolsa Mexicana de Valores.

2. **Secretaría de Hacienda y Crédito Público.** (2025). *Comunicado: Emisión de Notas Precapitalizadas (P-Caps)*. 29 de julio de 2025.

3. **Congreso de la Unión.** (2025). *Ley de Ingresos de la Federación 2025-2026*. Diario Oficial de la Federación.

### Literatura Técnica

4. **Moody's Ratings.** (2026). *Pemex Credit Analysis and Projections 2026-2029*. Moody's Analytics.

5. **International Monetary Fund.** (2025). *Fiscal Monitor: Mexico - Managing Contingent Liabilities*. IMF Publications.

6. **Banco de México.** (2025). *Reporte sobre el Sistema Financiero*. Banxico.

### Análisis Académico

7. **Centro de Investigación Económica y Presupuestaria.** (2025). *El Impacto Fiscal de las Empresas Productivas del Estado*. CIEP.

8. **México Evalúa.** (2025). *Auditoría de la Auditoría: Pemex y el Balance Fiscal*. México Evalúa A.C.

---

## 🔄 Changelog

### v1.0.0 (2026-03-03)
- 🚀 Lanzamiento inicial
- ✨ Índice RFC-SL implementado
- 📊 Dashboard interactivo completo
- 📱 Responsive design
- ♿ Accesibilidad WCAG AA
- 🖨️ Optimización para impresión
- 🔗 Compartir en redes sociales
- 💾 Descarga HTML autocontenido

---

<div align="center">

**Hecho con 📊 y ☕ en México**

[⬆️ Volver arriba](#-brief-de-riesgo-reconfiguración-de-pasivos-pemex)

---

**SocioNomics Lab** | Inteligencia Estratégica Independiente  
© 2026 | [socionomicslab.org](https://socionomicslab.org)

</div>
