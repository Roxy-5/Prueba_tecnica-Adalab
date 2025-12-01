![](https://github.com/Roxy-5/Evaluacion1-Adalab/blob/main/image.jpg?raw=true)
## 📊 Prueba técnica
Análisis exploratorio completo de un dataset de reservas hoteleras, incluyendo limpieza de datos, validación de requisitos de negocio y visualizaciones. 

Dataset: https://docs.google.com/spreadsheets/d/1rs_RJce7c4ig36f-t8JIgC_q1sp2-zdJ/edit?rtpof=true&sd=true&gid=1553229816#gid=1553229816

## 🎯 Objetivos
- Identificar y corregir problemas de calidad de datos.
- Validar reglas de negocio específicas.
- Generar insights mediante visualizaciones.
- Preparar datos para análisis posteriores.
  
## 🚀 Cómo usar
1. **Clona este repositorio.**
2. **Instala las librerías:**
    - seaborn
    - matplotlib
    - pandas
    - numpy
    - scipy

4. **Ejecuta las celdas de código una a una.**

## 📁 Estructura del Proyecto
```
├── Prueba_técnica.ipynb   # Notebook principal con análisis
├── bookings.csv           # Dataset original
├── README.md              # Este archivo
```

## 📈 Análisis Realizado
### 1. Limpieza de Datos
- ✅ Eliminación de registros sin autorización.
- ✅ Corrección de formatos de email inválidos.
- ✅ Imputación de valores nulos en columnas numéricas.
- ✅ Conversión de monedas a EUR.
- ✅ Eliminación de registros sin motivo obligatorio.

### 2. Validaciones de Negocio
- ✅ Control de duplicados por reserva.
- ✅ Verificación de campos obligatorios.
- ✅ Validación de formatos de email.
- ✅ Conversión unificada a euros.

### 3. Visualizaciones
- 📊 Distribución por estado de reservas
- 🥧 Análisis de monedas utilizadas 
- 📈 Top 10 clientes más activos
- 🗺️ Análisis por región geográfica (barras apiladas)
- 🔥 Heatmap de status vs región
- 📋 Principales categorías de motivos
- 📅 Evolución temporal de requests
- 💰 Análisis de importes por moneda (boxplots)
- 🔗 Correlación entre variables numéricas
![](https://github.com/user-attachments/assets/c01e8ad3-e12c-4e6f-81b0-9ee892ba822d)

## 📊 Principales Hallazgos
### Calidad de Datos
- **Dataset final**: 239,396 registros válidos.
- **Completitud**: 100% tras proceso de limpieza.
- **Duplicados**: Únicamente 2 registros (despreciable).
- **Nulos restantes**: 83 en campo opcional "Reason 2".

### Insights de Negocio
- **Moneda principal**: USD (95.5%)
- **Estado predominante**: Applied (92.4%)
- **Cliente más activo**: CLIENT1 con 84466 requests 
- **Región con más actividad**: Region 1 (36.0%)

## ⚠️ Limitaciones y Supuestos
- Campo "Reason 2" mantiene 83 nulos por ser opcional.
- Análisis temporal limitado por formato de fechas.
- Los códigos CLIENT1, CLIENT2, etc. representan clientes anonimizados.
- Los códigos Region 1, Region 2, etc. representan países anonimizados.
- La alta concentración en "OTHERS" indica procesos operacionales estándar.
- Issues técnicos/operacionales (<2%) están dentro de rangos normales.

## 📋 Próximos Pasos
- [ ] Subcategorizar "OTHERS" en categorías específicas. 
- [ ] Análisis predictivo de aprobación de requests.
- [ ] Segmentación de clientes por comportamiento y región.
- [ ] Análisis de estacionalidad y demanda en requests.
- [ ] Dashboard interactivo con Power BI/Tableau.

🪐 Autor

Rocío Ramírez
