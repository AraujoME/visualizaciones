<p align="center">
  <a href="https://araujome.github.io/visualizaciones/comparativapisamexico/">
    <img src="https://img.shields.io/badge/Demo-GitHub%20Pages-blue?logo=github" />
  </a>
  <a href="https://araujome.github.io/visualizaciones/">
    <img src="https://img.shields.io/badge/Portafolio-Visualizaciones-informational" />
  </a>
  <a href="https://www.oecd.org/pisa/">
    <img src="https://img.shields.io/badge/Datos-OCDE%20PISA-lightgrey" />
  </a>
  <img src="https://img.shields.io/badge/Periodo-2012--2022-yellowgreen" />
  <a href="https://opensource.org/license/MIT">
    <img src="https://img.shields.io/badge/Licencia-MIT-green" />
  </a>
</p>



# 📊 La Carrera Educativa  
### Comparativa PISA: Latinoamérica vs Líder Global (2012–2022)

Visualización interactiva que compara los resultados del programa **PISA (OCDE)** para México, Chile, Argentina y Colombia frente a **Singapur** como benchmark global, entre 2012 y 2022.

El proyecto combina **visualización de datos**, **análisis contextual** y **criterios metodológicos explícitos**, con énfasis en accesibilidad, transparencia y rigor interpretativo.

🔗 **Dashboard interactivo (GitHub Pages):**  
👉 https://araujome.github.io/visualizaciones/comparativapisamexico/

🔗 **Portafolio completo de visualizaciones:**  
👉 https://araujome.github.io/visualizaciones/

---

## 🎯 Objetivo del proyecto

Este dashboard busca:

- Visualizar la **brecha educativa estructural** entre Latinoamérica y el líder global.
- Mostrar la **evolución temporal** de los resultados PISA en Matemáticas, Lectura y Ciencias.
- Contextualizar los datos con **limitaciones metodológicas reales**.
- Evitar interpretaciones simplistas o deterministas de los puntajes.

💡 **Nota:** No es un ranking, sino una **herramienta de análisis comparado**.

---

## 🧠 Enfoque metodológico

### 📐 Interpretación de puntajes

Se utiliza la estimación estándar de la OCDE:

> **≈ 40 puntos PISA ≈ 1 año de escolaridad formal**  
> *(OCDE, PISA in Focus, 2012)*

- La brecha observada (~160–180 puntos) se interpreta como un **orden de magnitud** de **4 a 4.5 años de rezago académico**.
- Esta equivalencia es **pedagógica**, no una conversión lineal exacta.

### 🌍 Benchmark global

- **Singapur** se utiliza como referencia por su liderazgo sostenido en PISA.
- Se reconoce explícitamente como un **outlier institucional y cultural**:
  - Ciudad-estado
  - Alta centralización educativa
  - Baja heterogeneidad socioeconómica
- Sus resultados **no son replicables linealmente** en contextos latinoamericanos.

---

## ⚠️ Limitaciones reconocidas

El proyecto incorpora de forma explícita las principales limitaciones del uso de PISA:

1. **Sesgo de muestra (deserción)**  
   PISA evalúa solo estudiantes de 15 años escolarizados. En países con alta deserción, los alumnos más vulnerables quedan fuera, lo que puede sesgar los promedios al alza.

2. **Comparabilidad cultural**  
   Las pruebas estandarizadas pueden favorecer ciertos enfoques curriculares y culturales.

3. **Fotografía estática**  
   Los resultados reflejan un momento específico, no trayectorias completas de aprendizaje.

4. **Impacto COVID-19 (2022)**  
   En México, los cierres escolares se estiman en **≈170–180 días**, muy por encima del promedio global (~95 días), lo que se correlaciona con la caída en puntajes.

---

## 🕒 Cobertura temporal

| Año | Contexto clave |
|----|---------------|
| **2012** | Inicio de la transición hacia evaluaciones digitales |
| **2015** | Argentina excluida de agregados por problemas muestrales (visualización atenuada) |
| **2018** | Última medición pre-pandemia |
| **2022** | Resultados post-COVID-19 |

---

## 🧩 Tecnologías utilizadas

- **HTML5 / CSS3**
- **Tailwind CSS** (estilos y layout responsive)
- **Chart.js 4.x** + `chartjs-plugin-datalabels`
- **JavaScript Vanilla**
- **html2canvas** (exportación del dashboard a imagen)
- **Font Awesome** (iconografía)
- **Google Fonts – Outfit** (tipografía)

---

## ♿ Accesibilidad y UX

- **ARIA:** Slider temporal con atributos de accesibilidad completos.
- **Narrativa:** Textos explicativos dinámicos por año.
- **Feedback visual:** Leyenda adaptativa y tooltips informativos.
- **Diseño:** Colores contrastados y jerarquía visual clara.
- **Utilidad:** Exportación directa del dashboard como imagen `.png`.

---

## 📚 Fuentes oficiales

- **OCDE**
  - *PISA Results* (Volumes I): 2012, 2015, 2018, 2022  
  - *PISA in Focus* (2012): equivalencia puntos-años

- **UNICEF / UNESCO**
  - *COVID-19 y cierres de escuelas: Monitoreo del impacto educativo* (2021)

---

## 🧑‍💻 Autor

**Eric Araujo Martínez**  
Economista | MBA | Análisis de datos y visualización  
📍 Ciudad de México

- GitHub: https://github.com/araujome  
- LinkedIn: https://www.linkedin.com/in/ericaraujom/  
- X (Twitter): https://x.com/SocioNomicsLab  

---

## 📄 Licencias

Este proyecto utiliza un modelo de licencia dual:

- **Contenido y visualización:**  
  Creative Commons **CC BY-NC 4.0**  
  *(uso libre con atribución, no comercial)*

- **Código fuente:**  
  **Licencia MIT**

---

## 📝 Nota final

Este proyecto es deliberadamente **analítico, no prescriptivo**.  
Busca abrir preguntas informadas sobre educación, desigualdad y políticas públicas, no ofrecer soluciones simplistas ni comparaciones acríticas.
