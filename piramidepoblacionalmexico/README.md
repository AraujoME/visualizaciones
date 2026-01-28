# 🇲🇽 La Metamorfosis de México: Evolución Demográfica (1960-2050)

<div align="center">

![México Population Pyramid](https://img.shields.io/badge/Population-126M%20(2020)-blue)
![Data Source](https://img.shields.io/badge/Source-INEGI%20%7C%20CONAPO-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Data License](https://img.shields.io/badge/Content-CC%20BY--NC%204.0-orange)

**Visualización interactiva de la transición demográfica de México a través de pirámides poblacionales**

[Ver Demo](https://araujome.github.io/visualizaciones/) • [Reportar Bug](https://github.com/araujome/visualizaciones/issues) • [Solicitar Feature](https://github.com/araujome/visualizaciones/issues)

</div>

---

## 📊 Sobre el Proyecto

Una visualización interactiva que ilustra la dramática transformación demográfica de México desde 1960 hasta proyecciones al 2050. El proyecto muestra cómo México ha pasado de una pirámide poblacional expansiva (país joven) a una estructura en forma de urna (población envejecida).

### ✨ Características Principales

- 🎯 **13 años de datos**: Incluye censos (1960-2020), conteos intercensales (1995, 2005) y encuesta (2015)
- 📈 **Proyecciones validadas**: Basadas en CONAPO 2016-2050 (escenario medio)
- 🎨 **Interfaz interactiva**: Slider temporal para explorar la evolución demográfica
- 📱 **Diseño responsivo**: Optimizado para desktop, tablet y móvil
- 📥 **Exportación**: Descarga la gráfica como imagen PNG de alta calidad
- 📊 **Indicadores clave**: Tasa de dependencia, envejecimiento poblacional, distribución por sexo

### 🎬 Vista Previa

```
         85+  ▓▓░░░░░░░░░░░░░░░░░░░░░░░░▒▒▒
       80-84  ▓▓▓░░░░░░░░░░░░░░░░░░░░░░▒▒▒▒
       75-79  ▓▓▓▓░░░░░░░░░░░░░░░░░░░░▒▒▒▒▒
       70-74  ▓▓▓▓▓░░░░░░░░░░░░░░░░░▒▒▒▒▒▒▒
         ...
       10-14  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
        5-9   ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
        0-4   ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
              
              ▓ Hombres        ▒ Mujeres
```

---

## 🚀 Inicio Rápido

### Visualización en Línea

Simplemente abre el archivo HTML en tu navegador:

```bash
# Clona el repositorio
git clone https://github.com/araujome/visualizaciones.git

# Navega al directorio
cd visualizaciones

# Abre el archivo en tu navegador
open piramide_poblacional_mexico.html
```

### Servidor Local (Opcional)

Para desarrollo con live reload:

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js
npx http-server

# Abre http://localhost:8000
```

---

## 📁 Estructura del Proyecto

```
piramide-poblacional-mexico/
│
├── piramide_poblacional_mexico.html    # Archivo principal (standalone)
├── README.md                            # Este archivo
├── LICENSE                              # Licencia MIT (código)
├── LICENSE-CONTENT                      # CC BY-NC 4.0 (contenido)
│
└── docs/                                # (Opcional) Documentación adicional
    ├── metodologia.md                   # Metodología detallada
    ├── fuentes.md                       # Referencias y fuentes
    └── capturas/                        # Screenshots del proyecto
```

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Versión | Propósito |
|------------|---------|-----------|
| **HTML5** | - | Estructura |
| **TailwindCSS** | 3.x | Diseño y estilos |
| **Chart.js** | 4.x | Gráficas interactivas |
| **html2canvas** | 1.x | Exportación de imágenes |
| **Font Awesome** | 6.5.1 | Iconografía |
| **Google Fonts (Inter)** | - | Tipografía |

### Sin Dependencias Backend

✅ **100% Frontend** - No requiere servidor, base de datos ni API  
✅ **Standalone** - Todo está en un solo archivo HTML  
✅ **Sin Build** - No necesita webpack, npm ni compilación

---

## 📊 Fuentes de Datos

### Datos Históricos (INEGI)

| Año | Tipo | Población | Fuente |
|-----|------|-----------|--------|
| 1960 | Censo | 34.9 M | [INEGI Censo 1960](https://www.inegi.org.mx/programas/ccpv/1960/) |
| 1970 | Censo | 48.2 M | [INEGI Censo 1970](https://www.inegi.org.mx/programas/ccpv/1970/) |
| 1980 | Censo | 66.8 M | [INEGI Censo 1980](https://www.inegi.org.mx/programas/ccpv/1980/) |
| 1990 | Censo | 81.2 M | [INEGI Censo 1990](https://www.inegi.org.mx/programas/ccpv/1990/) |
| 1995 | Conteo | 91.2 M | [INEGI Conteo 1995](https://www.inegi.org.mx/programas/ccpv/1995/) |
| 2000 | Censo | 97.5 M | [INEGI Censo 2000](https://www.inegi.org.mx/programas/ccpv/2000/) |
| 2005 | Conteo | 103.3 M | [INEGI Conteo 2005](https://www.inegi.org.mx/programas/ccpv/2005/) |
| 2010 | Censo | 112.3 M | [INEGI Censo 2010](https://www.inegi.org.mx/programas/ccpv/2010/) |
| 2015 | Encuesta | 119.5 M | [INEGI Encuesta 2015](https://www.inegi.org.mx/programas/intercensal/2015/) |
| 2020 | Censo | 126.0 M | [INEGI Censo 2020](https://www.inegi.org.mx/programas/ccpv/2020/) |

### Proyecciones (CONAPO)

| Año | Población Proyectada | Fuente |
|-----|----------------------|--------|
| 2030 | 138.1 M | [CONAPO 2016-2050](https://www.gob.mx/conapo/documentos/proyecciones-de-la-poblacion-de-mexico-y-de-las-entidades-federativas-2016-2050) |
| 2040 | 143.1 M | Interpolación lineal |
| 2050 | 148.2 M | [CONAPO 2016-2050](https://www.gob.mx/conapo/documentos/proyecciones-de-la-poblacion-de-mexico-y-de-las-entidades-federativas-2016-2050) |

### 📚 Bibliografía Completa

1. Instituto Nacional de Estadística y Geografía (INEGI). (1960-2020). *Censos de Población y Vivienda*. México.
2. Instituto Nacional de Estadística y Geografía (INEGI). (1995, 2005). *Conteos de Población y Vivienda*. México.
3. Instituto Nacional de Estadística y Geografía (INEGI). (2015). *Encuesta Intercensal 2015*. México.
4. Consejo Nacional de Población (CONAPO). (2016). *Proyecciones de la Población de México 2016-2050*. México: SEGOB.
5. Consejo Nacional de Población (CONAPO). (2023). *Conciliación Demográfica de México 1950-2019 y Proyecciones 2020-2070*. México: SEGOB.

---

## 🎯 Características Técnicas

### Precisión de los Datos

✅ **Calibración exacta**: Todos los arrays de datos suman exactamente los totales oficiales del INEGI  
✅ **Validación cruzada**: Proyecciones verificadas contra documentos oficiales de CONAPO  
✅ **Transparencia**: Fuente explícita para cada año de datos  
✅ **Diferenciación visual**: Colores distintos para censos, conteos y proyecciones

### Indicadores Demográficos

**Tasa de Dependencia**
```
Fórmula: (Población 0-14 años + Población 65+ años) / Población 15-64 años × 100
Interpretación: Personas dependientes por cada 100 en edad productiva
```

**Nivel de Envejecimiento**
```
Fórmula: (Población 65+ años) / Población total × 100
Interpretación: Porcentaje de población en edad avanzada
```

### Optimizaciones

- ⚡ Renderizado eficiente con Chart.js
- 📦 Assets cargados desde CDN (caché del navegador)
- 🎨 Animaciones CSS suaves
- 📱 Breakpoints responsivos
- 🖼️ Exportación de alta calidad (scale: 2)

---

## 🎨 Personalización

### Cambiar Colores

Modifica las variables en la sección de Chart.js:

```javascript
datasets: [
    { 
        backgroundColor: '#4f46e5',  // Color hombres (azul índigo)
        // ... 
    },
    { 
        backgroundColor: '#e11d48',  // Color mujeres (rosa)
        // ...
    }
]
```

### Ajustar Rango del Eje X

```javascript
scales: {
    x: { 
        min: -8,  // Límite izquierdo (hombres)
        max: 8,   // Límite derecho (mujeres)
        // ...
    }
}
```

### Modificar Grupos de Edad

```javascript
const ageGroups = ['85+', '80–84', '75–79', /* ... */ '0–4'];
```

---

## 📈 Roadmap

### Versión Actual: 1.0

- [x] Visualización interactiva con slider
- [x] 13 años de datos (1960-2050)
- [x] Indicadores demográficos
- [x] Exportación de imágenes
- [x] Diseño responsivo
- [x] Metodología documentada

### Próximas Versiones

- [ ] **v1.1**: Comparación entre múltiples años simultáneamente
- [ ] **v1.2**: Animación automática tipo "time-lapse"
- [ ] **v1.3**: Descargar datos en CSV/Excel
- [ ] **v2.0**: Comparación con otros países de LATAM
- [ ] **v2.1**: Proyecciones alternativas (escenarios alto/bajo)
- [ ] **v2.2**: Análisis por entidad federativa
- [ ] **v3.0**: Versión interactiva con D3.js
- [ ] **v3.1**: Dashboard con múltiples indicadores

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Este proyecto está en constante mejora.

### Cómo Contribuir

1. **Fork** el repositorio
2. **Crea** una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. **Push** a la rama (`git push origin feature/AmazingFeature`)
5. **Abre** un Pull Request

### Áreas de Contribución

- 🐛 Reportar bugs o inconsistencias en los datos
- 💡 Sugerir nuevas características
- 📝 Mejorar la documentación
- 🎨 Optimizar diseño y UX
- 📊 Validar datos contra fuentes oficiales
- 🌍 Traducir a otros idiomas
- ♿ Mejorar accesibilidad

### Validación de Datos

Si encuentras discrepancias en los datos:

1. Verifica contra las fuentes oficiales (INEGI/CONAPO)
2. Abre un issue con:
   - Año afectado
   - Valor actual vs. valor correcto
   - Fuente oficial (con enlace)
   - Cálculo de la diferencia

---

## 📄 Licencias

Este proyecto utiliza un modelo de **licencia dual**:

### Código (MIT License)

El código fuente (HTML, CSS, JavaScript) está bajo **MIT License**.

```
Copyright (c) 2026 Eric Araujo Martínez (@SocioNomicsLab)

Se concede permiso para usar, copiar, modificar y distribuir este software...
```

Ver archivo `LICENSE` para más detalles.

### Contenido (CC BY-NC 4.0)

El contenido educativo (análisis, visualizaciones, textos) está bajo **Creative Commons Attribution-NonCommercial 4.0**.

**Puedes:**
- ✅ Compartir — copiar y redistribuir el material
- ✅ Adaptar — remezclar, transformar y construir sobre el material

**Bajo los siguientes términos:**
- 👤 **Atribución** — Debes dar crédito apropiado
- 🚫 **NoComercial** — No puedes usar el material con fines comerciales

Ver archivo `LICENSE-CONTENT` para más detalles.

---

## 👨‍💻 Autor

**Eric Araujo Martínez**  
*Analista de Datos & Visualización*

- 🌐 Website: [araujome.github.io](https://araujome.github.io/visualizaciones/)
- 💼 LinkedIn: [linkedin.com/in/ericaraujom](https://www.linkedin.com/in/ericaraujom/)
- 🐦 Twitter/X: [@SocioNomicsLab](https://x.com/SocioNomicsLab)
- 📧 GitHub: [@araujome](https://github.com/araujome)

---

## 🙏 Agradecimientos

- **INEGI** - Por mantener datos censales de acceso público
- **CONAPO** - Por las proyecciones demográficas oficiales
- **Chart.js** - Librería excelente para visualizaciones
- **Tailwind CSS** - Framework de diseño productivo
- **Comunidad Open Source** - Por las herramientas que hacen esto posible

---

## 📞 Contacto y Soporte

### ¿Encontraste un bug?
Abre un [issue en GitHub](https://github.com/araujome/visualizaciones/issues/new?template=bug_report.md)

### ¿Tienes una pregunta?
Usa [GitHub Discussions](https://github.com/araujome/visualizaciones/discussions)

### ¿Quieres colaborar?
Revisa nuestro [roadmap](#-roadmap) y [guía de contribución](#-contribuciones)

---

## ⭐ Agradece con una Estrella

Si este proyecto te resultó útil, considera darle una ⭐ en GitHub. ¡Ayuda a que más personas lo descubran!

---

<div align="center">

**Hecho con ❤️ en México 🇲🇽**

[⬆ Volver arriba](#-la-metamorfosis-de-méxico-evolución-demográfica-1960-2050)

</div>
