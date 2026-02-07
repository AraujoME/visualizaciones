Mercado Laboral Universitario: Ingresos vs. Popularidad 📊

Una visualización interactiva de datos que explora la evolución del mercado laboral para profesionistas en México. Este proyecto cruza variables de Ingreso Promedio Mensual con la Población Ocupada (Saturación) para identificar carreras de nicho, oportunidades emergentes y sectores saturados.

Incluye datos históricos (2018-2024) y proyecciones estimadas (2025-2030) basadas en tendencias económicas globales.

🚀 Características

Gráfica de Dispersión (Scatter Plot): Visualización clara de cuadrantes (Ingresos vs. Popularidad).

Línea de Tiempo Interactiva: Slider para navegar año por año desde 2018 hasta 2030 con interpolación suave de datos.

Diseño Responsivo: Optimizado para escritorio y dispositivos móviles, con ajuste dinámico de etiquetas y fuentes.

Categorización por Colores: Segmentación visual por áreas de estudio (Ingenierías, Salud, Negocios, Humanidades).

Exportación: Funcionalidad integrada para descargar la visualización actual como imagen PNG de alta resolución.

Notas Contextuales: Badges automáticos que indican cuándo se están visualizando datos proyectados.

🛠️ Tecnologías Utilizadas

Este proyecto se ha construido utilizando una arquitectura de archivo único (Single File Component) para facilitar su portabilidad y despliegue.

HTML5 / CSS3

Tailwind CSS: Para el estilizado y diseño responsivo.

Chart.js (v4.x): Motor principal de renderizado de gráficas.

Chart.js Datalabels: Para el manejo inteligente de etiquetas en las burbujas.

Chart.js Annotation: Para dibujar las zonas de "Alto Valor" y "Mercado Saturado".

html2canvas: Para la funcionalidad de captura de pantalla y descarga.

FontAwesome & Google Fonts: Tipografía e iconografía.

📋 Estructura de Datos

Los datos se estructuran en un objeto db dentro del script principal, conteniendo "snapshots" de años clave. El sistema utiliza una función de interpolación lineal (interpolateData) para calcular la posición y tamaño de las burbujas en los años intermedios, proporcionando una animación fluida.

// Ejemplo de estructura de datos
{
    x: 980,   // Población Ocupada (Miles)
    y: 12500, // Salario Promedio ($ MXN)
    r: 15,    // Radio (Tasa de ocupación relativa)
    label: 'Admin. Empresas',
    type: 'negocios',
    align: 'top' // Alineación forzada para evitar solapamientos
}


📦 Instalación y Uso

Clonar o Descargar:
Simplemente descarga el archivo carreras_mexico.html.

Ejecutar:
Abre el archivo directamente en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari). No requiere un servidor local (backend) para funcionar, ya que todas las librerías se cargan vía CDN.

📄 Licencias

Este proyecto opera bajo un modelo de licencia dual:

Código Fuente (Software): Bajo la Licencia MIT. Eres libre de usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar y/o vender copias del software.

Contenido y Datos (Visualización): Bajo la licencia Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC 4.0). Puedes compartir y adaptar el material, siempre que des crédito al autor y no lo uses para fines comerciales.

Autor: Eric Araujo Martínez (@SocioNomicsLab)

📚 Referencias Bibliográficas (APA)

Para aquellos interesados en utilizar la metodología o los datos de este proyecto para investigación académica, se citan las fuentes originales utilizadas para la construcción de la base de datos y las proyecciones:

Instituto Nacional de Estadística y Geografía (INEGI). (2024). Encuesta Nacional de Ocupación y Empleo (ENOE), indicadores estratégicos. Recuperado de https://www.inegi.org.mx/programas/enoe/15ymas/

Instituto Mexicano para la Competitividad (IMCO). (2024). Compara Carreras: Índice de Calidad de la Inversión. Recuperado de https://imco.org.mx/comparacarreras/

Secretaría del Trabajo y Previsión Social (STPS). (n.d.). Observatorio Laboral: Panorama profesional por carreras. Gobierno de México. Recuperado de https://www.observatoriolaboral.gob.mx/

World Economic Forum. (2023). The Future of Jobs Report 2023. Geneva: World Economic Forum. Recuperado de https://www.weforum.org/publications/the-future-of-jobs-report-2023/

Última actualización: Febrero 2026

Si este proyecto te resulta útil para investigación, docencia o análisis público, puedes citarlo como:

> Araujo, E. (2025). Mercado Laboral Universitario en México (2018–2024). SocioNomicsLab.

---
