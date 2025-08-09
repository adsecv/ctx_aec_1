# Análisis de Churn en Clientes de Telecomunicaciones

## 📌 Descripción
Este proyecto analiza datos de clientes de una empresa de telecomunicaciones para identificar factores asociados al **churn** (abandono de clientes).  
El trabajo se realizó en **Google Colab** usando Python.

## 🛠 Proceso realizado
1. **Carga de datos** desde archivo fuente.
2. **Transformación y limpieza**:
   - Eliminación de valores nulos.
   - Verificación y eliminación de duplicados.
   - Normalización de valores en columnas categóricas.
   - Conversión de servicios a variables binarias.
   - Creación de la columna **`Cuentas_Diarias`**.
3. **Análisis exploratorio**:
   - Estadísticas descriptivas.
   - Visualización de datos.
   - Cálculo de correlaciones.
4. **Generación de informe** con hallazgos y estrategias.

## 📊 Resumen de resultados
- **Clientes analizados:** 7,043  
- **Churn:** 26.5% abandonaron, 73.5% permanecieron.  
- **Factores de mayor riesgo:** contratos mes a mes, pagos con cheque electrónico, fibra óptica, cargos altos, baja permanencia.  
- **Factores protectores:** contratos largos, más servicios, soporte técnico, seguridad en línea.  
- **Momento crítico:** primeros 6 meses, con pico de churn del 62% a los 2 meses.

## 📦 Librerías utilizadas
- pandas  
- seaborn  
- matplotlib  
- requests  
- plotly.express
