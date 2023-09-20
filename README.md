# Análisis de Ventas [Proyecto 1 Big Data y ML (UPSO)]

Este repositorio contiene un análisis de las ventas de Amazon en Estados Unidos durante el año 2019. El análisis se divide en varios pasos, que se detallan a continuación:

## Pasos del Análisis

### 1. Carga de Datos
Se cargan los datos de ventas desde archivos CSV correspondientes a diferentes meses.

### 2. Limpieza de Datos
Los datos se someten a una limpieza que implica la eliminación de valores no numéricos y filas incompletas.

### 3. Preparación de Datos
Se ajustan los tipos de datos de cada atributo y se extraen características importantes como meses, horas, ciudades, etc.

### 4. Análisis de Datos
Se realiza un análisis exploratorio de datos para responder preguntas como: 
- ¿Cómo variaron las ventas a lo largo de los diferentes meses?
- ¿Hubo algún mes que se destacó en términos de ventas?
- ¿Cuál es el ingreso total generado por mes?

### 5. Visualización de Datos
Se utilizan gráficos y visualizaciones para representar los resultados de los análisis, incluyendo gráficos de barras, gráficos de burbujas y gráficos de ingresos totales por mes.

## Librerías y Recursos Utilizados
Para llevar a cabo este análisis, se utilizan las siguientes librerías y recursos:
- `os` para la manipulación de rutas de archivos.
- `pandas` para la manipulación y análisis de datos.
- `plotly.graph_objects` y `plotly.express` para la creación de visualizaciones interactivas.
- `make_subplots` para la creación de subgráficos.

### Estructura de Archivos
Los datos se encuentran almacenados en un directorio propio denominado "Dataset de ventas2". Cada archivo CSV en este directorio representa las ventas de un mes específico.

### Resumen de Resultados
El análisis revela el comportamiento de las ventas de Amazon en Estados Unidos a lo largo de 2019, destacando los meses con mayor actividad y los ingresos totales generados. Los resultados se visualizan de manera clara y concisa para comprender fácilmente el rendimiento de ventas de Amazon en ese año.

Dentro del repositorio también se encuentra un informe detallado de todo lo analizado ver: Informe_Proyecto1_Analisis_Ventas_Ivan_Tapia.pdf.

Para obtener más detalles y visualizar las gráficas generadas, por favor, revise y ejecute el código de este repositorio en colab.
