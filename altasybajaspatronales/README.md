# 🏗️ Dinámica Laboral IMSS: La “Ilusión” del Empleo Formal

**Un análisis de la distorsión estadística provocada por la Reforma de Plataformas Digitales frente a la realidad orgánica del mercado laboral en México (2023–2025).**

🔗 **[Ver Visualización Interactiva](https://araujome.github.io/visualizaciones/altasybajaspatronales/)**

---

## 🧐 Sobre el Estudio

A finales de 2025, las cifras del IMSS mostraron un comportamiento atípico: un **“pico histórico” de creación de empleo en noviembre**, seguido inmediatamente por una **caída patronal y estacional**.

Este proyecto desglosa los datos oficiales para **separar el crecimiento administrativo** (formalización por decreto de repartidores y choferes de plataformas digitales) del **crecimiento orgánico** (nuevas plazas reales), revelando una **tendencia preocupante de cierre de microempresas** en México.

---

## 📊 Hallazgos Clave

El tablero interactivo permite visualizar **dos realidades contradictorias**:

| Indicador              | Dato (Nov–Dic 2025) | Interpretación SocioNomics |
|------------------------|---------------------|-----------------------------|
| **Empleos Nuevos**     | 🟢 +1,326,000        | **Efecto administrativo.** Aproximadamente el 90% corresponde a la regularización de trabajadores de plataformas, no a nuevas vacantes productivas. |
| **Registros Patronales** | 🔴 −34,748        | **Destrucción real.** Caída neta de empleadores durante el sexenio. |
| **Empleo Orgánico**    | 🟡 Estancado         | Sin el “ajuste por plataformas”, el crecimiento laboral es marginal. |

**Veredicto:**  
Mientras el gobierno celebra cifras récord de afiliación al IMSS, el **tejido empresarial —especialmente las PyMEs— se contrae** debido al aumento de costos laborales y a una mayor fiscalización. Esto se traduce en una **pérdida estimada de ~139,000 empleos tradicionales**.

---

## 🛠️ Metodología y Fuentes

Este análisis se rige por el principio de **Rigor Estadístico**.

### Fuente Primaria
- Comunicados mensuales de **Puestos de Trabajo y Patrones Afiliados** del  
  **Instituto Mexicano del Seguro Social (IMSS)**.

### Periodo Analizado
- **Enero 2023 – Diciembre 2025**

### Procesamiento de Datos
- Se aisló el volumen de afiliados provenientes de la **Prueba Piloto y Reforma de Personas Trabajadoras del Hogar y Plataformas Digitales** para depurar la serie histórica.
- La pérdida de empleo orgánico se estimó multiplicando la **baja neta de patrones** por el **factor promedio de ocupación en micronegocios (3.8–4.2 personas)**, con base en la **ENAMIN (INEGI)**.

---

## 💻 Stack Tecnológico

- **Visualización:** Chart.js 4.x + `chartjs-plugin-annotation` para resaltar hitos legislativos.
- **Interfaz:** HTML5 + Tailwind CSS (diseño responsivo y minimalista).
- **Interacción:** Interruptor lógico para activar/desactivar la capa de datos de **Plataformas Digitales**.

---

## ⚖️ Licenciamiento y Autoría

### Contenido y Análisis
Este trabajo se distribuye bajo la licencia  
**Creative Commons Atribución–NoComercial 4.0 Internacional (CC BY-NC 4.0)**.  
Puedes compartirlo y adaptarlo **citando la fuente**, sin fines comerciales.

### Código Fuente
El código subyacente se publica bajo licencia **MIT**.

---

**Elaborado por:**  
**Eric Araujo Martínez** ([@SocioNomicsLab](https://github.com/araujome))  
*Intelligence for Social Action*
