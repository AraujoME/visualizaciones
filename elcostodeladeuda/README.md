# El Costo Real de la Deuda Pública

Análisis comparativo entre el costo histórico del FOBAPROA y el escenario proyectado si el gobierno asume formalmente las pérdidas acumuladas en Pemex, CFE y NAIM.

## Descripción

Esta visualización compara dos eventos fiscales de gran impacto en México:
1. **FOBAPROA-IPAB (1995-2024)**: Rescate bancario histórico y su costo real
2. **Pérdidas estatales (2019-2025)**: Escenario proyectado si se formalizan como deuda pública

## ¿Qué significa "asumir como deuda pública formal"?

### Estado actual (2025)
Las pérdidas de Pemex, CFE y el costo de cancelación del NAIM están registradas en:
- Balances contables de las empresas estatales
- **NO son deuda pública oficial**
- **NO generan pagos de intereses formalizados**

### Escenario "FOBAPROA 2.0"
Si estas empresas no pueden cubrir sus obligaciones, el gobierno tendría que:
1. **Emitir bonos soberanos** para cubrir las pérdidas
2. **Pagar intereses** durante 20-30 años (como sucedió con IPAB)
3. **Resultado**: El costo total se multiplica 1.5-2x por los intereses compuestos

### Alternativa
- Continuar con inyecciones anuales de capital
- Menos visible contablemente
- Costo fiscal similar o mayor a largo plazo
- Menor transparencia pública

## Datos y Metodología

### FOBAPROA-IPAB (Datos Reales)

**Capital Original**: $550,000 millones de pesos
- Rescate bancario de 1995
- Crisis financiera mexicana

**Intereses Pagados/Por Pagar**: $2.45 billones de pesos
- Pagos históricos (1995-2024): ~$1.3 billones
- Deuda restante: ~$1.1 billones
- Plazo: 30 años (vence ~2025-2030)

**Costo Total Real**: $3.0 billones de pesos

**Fuentes**:
- CEFP - Saldo Histórico del IPAB
- SHCP - Costo Financiero de la Deuda

### Pérdidas Pemex/CFE/NAIM (Proyección)

**Capital (Pérdidas Documentadas)**: $2.1 billones de pesos

Desglose:
- **Pemex**: ~$1.5 billones (Estados Financieros BMV 4T-2024, 1T-2025)
- **CFE**: ~$300,000 millones (Estados Financieros consolidados)
- **NAIM**: ~$331,000 millones (ASF - costo de cancelación ajustado)

**Intereses Proyectados**: $3.15 billones de pesos*

**Costo Total Proyectado**: $5.25 billones de pesos

### Metodología de Proyección (*)

**Escenario hipotético**: Si el gobierno emitiera bonos soberanos para cubrir los $2.1B en pérdidas:

**Asunciones**:
- **Plazo**: 20 años (estándar para deuda de largo plazo)
- **Tasa de interés**: 9.0% anual
  - Basada en rendimiento promedio actual de bonos Pemex
  - Costo de financiamiento del gobierno mexicano en mercados internacionales
- **Modelo**: Interés compuesto, similar al esquema IPAB

**Resultado**:
- Intereses acumulados: +$3.15 billones
- Costo total: $5.25 billones (2.5x el capital original)

**⚠️ IMPORTANTE**: Esta es una **proyección de escenario**, no una deuda actual. Las pérdidas permanecen en los balances de las empresas estatales.

## Fuentes Oficiales

### Datos FOBAPROA-IPAB
- **CEFP** (Centro de Estudios de las Finanzas Públicas) - Saldo Histórico del IPAB
- **SHCP** (Secretaría de Hacienda y Crédito Público) - Costo Financiero de la Deuda

### Datos Pérdidas Estatales
- **BMV** (Bolsa Mexicana de Valores) - Estados Financieros Pemex/CFE (4T-2024, 1T-2025)
- **ASF** (Auditoría Superior de la Federación) - Costo de cancelación NAIM
- **Reportes financieros consolidados** de empresas estatales

### Metodología Financiera
- **Cálculo actuarial** estándar para bonos de largo plazo
- **Tasa de referencia**: Bonos gubernamentales mexicanos y Pemex
- **Modelo**: Interés compuesto sobre 20 años

## Limitaciones y Consideraciones

### Este análisis NO incluye:
- Efectos inflacionarios (salarios nominales vs. reales)
- Variaciones futuras en tasas de interés
- Posibles reestructuraciones de deuda
- Cambios en política fiscal o energética
- Valor de activos de las empresas estatales

### Escenarios alternativos no modelados:
- Capitalización exitosa de Pemex/CFE
- Venta de activos estatales
- Crecimiento económico que reduzca ratio deuda/PIB
- Reformas estructurales en empresas públicas

## Interpretación

### Lo que los datos muestran:
- El rescate FOBAPROA costó $3B en total (5.5x el capital original)
- Las pérdidas actuales en empresas estatales suman $2.1B
- **Si se formalizaran** como deuda pública, el costo proyectado sería $5.25B

### Lo que los datos NO dicen:
- Que estas pérdidas **se convertirán** automáticamente en deuda pública
- Que el gobierno **debe** formalizar estas pérdidas vía bonos
- Que no existen alternativas de financiamiento o reestructura

### Dos caminos posibles:

**Opción 1: Formalizar vía bonos** (modelo IPAB)
- ✅ Transparencia contable
- ✅ Pago estructurado a largo plazo
- ❌ Costo elevado por intereses

**Opción 2: Inyecciones de capital anuales**
- ✅ No aumenta deuda pública oficial
- ❌ Menos transparente
- ❌ Costo fiscal similar o mayor
- ❌ Presión presupuestal año con año

**En ambos casos**: El costo lo absorbe el erario público. La diferencia está en la forma contable y la transparencia.

## Visualización

La gráfica de barras apiladas muestra:
- **Eje vertical**: Billones de pesos (MXN)
- **Barras grises**: Capital original o pérdida documentada
- **Barras rojas**: Intereses pagados (FOBAPROA) o proyectados (Pemex/CFE/NAIM)
- **Etiquetas**: 
  - Verde "REAL" = datos históricos confirmados
  - Amarillo "PROYECCIÓN" = escenario hipotético

## Tecnologías Utilizadas

- **HTML5** + **Tailwind CSS** para diseño responsive
- **Chart.js** para visualización de datos
- **Chart.js Datalabels** para etiquetas en gráficas
- **html2canvas** para exportación de imágenes
- **Font Awesome** para iconografía

## Uso

### Visualización en línea
Abrir `index.html` en cualquier navegador moderno.

### Descarga de imagen
Usar el botón "Guardar Imagen" en la interfaz para exportar la visualización en alta resolución (PNG, 3x scale).

## Licencias

### Contenido y Visualización
**Creative Commons BY-NC 4.0**
- ✅ Compartir y adaptar con atribución
- ❌ Uso comercial no permitido

### Código Fuente
**MIT License**
- ✅ Uso, modificación y distribución libre
- ✅ Incluir en proyectos comerciales
- ℹ️ Sin garantías

## Autor

**Eric Araujo Martínez** (@SocioNomicsLab)

- GitHub: [@araujome](https://github.com/araujome)
- LinkedIn: [ericaraujom](https://www.linkedin.com/in/ericaraujom/)
- X/Twitter: [@SocioNomicsLab](https://x.com/SocioNomicsLab)

## Disclaimer

Esta visualización presenta un **análisis de escenario** con fines educativos y de debate público. No constituye:
- Asesoría financiera o de inversión
- Predicción de política fiscal
- Postura política partidista
- Recomendación de acción gubernamental

Los datos provienen de fuentes oficiales públicas. Las proyecciones son ejercicios analíticos basados en metodología financiera estándar. La interpretación de estos datos puede variar según el contexto macroeconómico y las decisiones de política pública.

---

**Última actualización**: Febrero 2025  
**Versión**: 2.0 (con explicación de deuda soberana)
