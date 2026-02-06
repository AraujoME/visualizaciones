<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-10b981?style=for-the-badge">
  <img src="https://img.shields.io/badge/Data-INEGI%20%7C%20STPS%20%7C%20IMCO-3b82f6?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-f59e0b?style=for-the-badge">
  <img src="https://img.shields.io/badge/Code-MIT-f43f5e?style=for-the-badge">
</p>

# Mercado Laboral Universitario en México (2018–2024)

Visualización interactiva que analiza la relación entre:

- **Ingreso promedio mensual (MXN nominales)**
- **Población ocupada por carrera (miles de personas)**
- **Tasa de ocupación (representada por el tamaño de la burbuja)**

El objetivo es identificar patrones de **saturación, rentabilidad relativa y nichos de alto valor** dentro del mercado laboral mexicano.

🔗 **Visualización en línea:**  
https://araujome.github.io/visualizaciones/

🔗 **Autor:**  
Eric Araujo Martínez  
https://www.linkedin.com/in/ericaraujom/  
https://github.com/araujome  
https://x.com/SocioNomicsLab  

---

## 📊 ¿Qué muestra la gráfica?

La visualización cruza tres dimensiones clave:

| Variable | Representación |
|----------|---------------|
| Salario promedio mensual | Eje vertical |
| Población ocupada (miles) | Eje horizontal |
| Tasa de ocupación | Tamaño de la burbuja |

Esto permite distinguir cuatro dinámicas estructurales:

- **Alto ingreso + baja saturación** → Nichos de alto valor  
- **Alta saturación + ingreso medio/bajo** → Mercados competidos  
- **Sectores tecnológicos** → Desplazamiento hacia cuadrantes superiores  
- **Carreras tradicionales** → Estancamiento relativo

La línea de tiempo (2018–2024) permite observar la evolución estructural del mercado laboral.

---

## 🧠 Metodología

### Selección de muestra
- 12 carreras con mayor matrícula nacional (~40% del total)
- 3 carreras emergentes (Ciencia de Datos, Energías Renovables, etc.) para contraste estructural

### Fuentes
- INEGI – ENOE  
- STPS – Observatorio Laboral  
- IMCO – Compara Carreras  
- Datos 2024 preliminares

### Notas técnicas
- Los salarios están expresados en **pesos mexicanos nominales**.
- No están ajustados por inflación.
- Los datos intermedios (2019, 2021, 2023) se estiman mediante interpolación lineal entre años observados.
- La visualización utiliza Chart.js con plugins de anotación y datalabels.

---

## ⚙️ Stack Tecnológico

- HTML5
- TailwindCSS
- Chart.js
- chartjs-plugin-datalabels
- chartjs-plugin-annotation
- html2canvas

---

## 📈 Interpretación Responsable

Este proyecto no pretende determinar la “mejor carrera”, sino mostrar:

- Tendencias de saturación relativa
- Diferenciales salariales promedio
- Dinámicas sectoriales emergentes

Los salarios promedio no reflejan distribución interna, informalidad ni brechas regionales.

---

## 📜 Licencias

**Contenido (datos, análisis y visualización):**  
Creative Commons CC BY-NC 4.0  
http://creativecommons.org/licenses/by-nc/4.0/

**Código:**  
MIT License  
https://opensource.org/license/MIT

---

## 👤 Autor

Eric Araujo Martínez  
Data Intelligence | SocioNomicsLab  

Si este proyecto te resulta útil para investigación, docencia o análisis público, puedes citarlo como:

> Araujo, E. (2025). Mercado Laboral Universitario en México (2018–2024). SocioNomicsLab.

---
