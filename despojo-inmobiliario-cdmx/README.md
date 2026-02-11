# Despojo Inmobiliario en CDMX  
## Realidad vs. Oficialidad (2015–2025)

Visualización interactiva que contrasta las **carpetas de investigación oficiales por despojo** en la Ciudad de México con una **estimación real basada en la cifra negra de no denuncia**.

El proyecto integra **periodismo de datos, análisis socioeconómico y visualización interactiva** para evidenciar la brecha entre la estadística administrativa y la posible magnitud real del fenómeno.

---

## 🌐 Visualización en vivo

- **Dashboard principal:**  
  https://araujome.github.io/visualizaciones/despojo-inmobiliario-cdmx/

- **Catálogo completo de visualizaciones:**  
  https://araujome.github.io/visualizaciones/

- **Repositorio del proyecto:**  
  https://github.com/AraujoME/visualizaciones

---

## 🧠 Enfoque del análisis

La visualización presenta dos lecturas complementarias:

### 1. Vista Oficial
Carpetas de investigación registradas por el **SESNSP** para el delito de despojo en la CDMX.

### 2. Vista Realidad
Estimación del total de delitos considerando una **cifra negra de 95.1%**,  
calculada por **México Evalúa** a partir de la **ENVIPE (INEGI)**.

**Fórmula aplicada:**
Total_real = oficial ÷ (1 − 0.951) ≈ oficial × 20.4

Esta estimación **no representa conteos observados**, sino una **proyección estadística del sub-registro de denuncia**.

---

## 📊 Qué permite observar

- Evolución anual del despojo en CDMX **2015–2025**
- Comparación entre:
  - denuncias oficiales
  - incidencia estimada real
- Segmentación visual por **administración de gobierno**
- Identificación de patrones clave:
  - **Pico de incidencia en 2021**
  - **Meseta alta posterior**
  - **Arranque elevado de la administración actual**

---

## 🛠️ Tecnologías utilizadas

- **HTML5**
- **Tailwind CSS**
- **Chart.js 4**
- Plugins:
  - `chartjs-plugin-datalabels`
  - `chartjs-plugin-annotation`
- **html2canvas** para exportación de la visualización
- **GitHub Pages** para despliegue público

---

## 📚 Fuentes de datos

- **SESNSP – Incidencia delictiva**  
  https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva  

- **México Evalúa – Hallazgos y cifra negra (ENVIPE)**  
  https://www.mexicoevalua.org/hallazgos-2023/  

- **INEGI – ENVIPE**  
  https://www.inegi.org.mx/programas/envipe/  

---

## ⚖️ Nota metodológica

La estimación de incidencia real:

- se basa en **modelación estadística del sub-registro**,  
- **no atribuye causalidad directa** a administraciones específicas,  
- busca **dimensionar la magnitud potencial del fenómeno** y enriquecer el debate público con evidencia cuantitativa.

---

## 👤 Autor

**Eric Araujo Martínez**  
Economista · Estratega de Datos · AI-Augmented Analyst  

- GitHub: https://github.com/AraujoME  
- X (Twitter): https://x.com/SocioNomicsLab  
- LinkedIn: https://www.linkedin.com/in/ericaraujom/

---

## 📄 Licencia

- **Contenido y análisis:** CC BY-NC 4.0  
- **Código fuente:** MIT License

---

## 🚀 Propósito del proyecto

Este trabajo forma parte de **SocioNomicsLab**,  
una iniciativa de inteligencia económica orientada a:

- auditar realidades sociales, económicas y de seguridad,  
- traducir datos complejos en narrativa pública comprensible,  
- fortalecer la conversación pública con **evidencia cuantitativa rigurosa**.

---

> **La estadística administrativa muestra lo que se denuncia.  
> La cifra negra sugiere lo que realmente ocurre.**
