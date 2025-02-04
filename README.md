# megaline_plan_analysis
Análisis estadístico de datos - Megaline (operador de telecomunicaciones) / Statistical Data Analysis - Megaline (Telecommunications Operator).

Proyecto hecho para TripleTen (Bootcamp online) - Sprint 5. Análisis estadístico de datos / Project completed for TripleTen (Online Bootcamp) - Sprint 5. Statistical Data Analysis.

### Descripción del proyecto / Project Description
Este proyecto tiene el objetivo de analizar el comportamiento de los usuarios de Megaline, una empresa de telecomunicaciones que ofrece dos tarifas de prepago: Surf y Ultimate. El análisis permitirá determinar qué tarifa genera más ingresos, basado en el comportamiento de los clientes y utilizando pruebas estadísticas para probar hipótesis sobre los ingresos y los usuarios de diferentes regiones.

## Estructura del Proyecto

### Introducción
1. Objetivo: Analizar el comportamiento de los usuarios de Megaline para determinar cuál tarifa genera más ingresos.
2. Datos: El dataset incluye información sobre 500 usuarios, como detalles personales, uso de llamadas, mensajes de texto e internet, y sus planes de tarifa.

### Preparación de los Datos
1. Conversiones de Tipos de Datos: Asegurar de que las columnas como las fechas y los números sean del tipo adecuado para evitar errores en los cálculos.
2. Eliminación de Errores: Verificar y limpiar los datos para corregir valores erróneos o faltantes.
3. Cálculo de Ingresos: Calcular los ingresos mensuales para cada usuario, considerando las tarifas de llamadas, SMS y datos que exceden los límites.

### Análisis de Datos
1. Comportamiento de los Usuarios: Calcular la media, varianza y desviación estándar de los minutos, SMS y datos utilizados mensualmente para cada tarifa.
2. Visualización: Utilizar histogramas y otros gráficos para visualizar la distribución del uso entre los usuarios de cada tarifa.

### Prueba de Hipótesis
- Hipótesis 1: El ingreso promedio de los usuarios de las tarifas Ultimate y Surf es diferente.
- Hipótesis 2: El ingreso promedio de los usuarios en la región Nueva York-Nueva Jersey es diferente al de otras regiones.
- Establecer el valor de alfa y las hipótesis nula y alternativa.

## Herramientas Utilizadas
- Python: Para el análisis de datos, incluyendo librerías como Pandas, NumPy, y Matplotlib.
- Jupyter Notebook: Para la estructura del proyecto y la integración del código y las explicaciones.

