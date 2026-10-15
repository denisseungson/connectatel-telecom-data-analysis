# Análisis de Datos de Telecomunicaciones – ConnectaTel
📊 Análisis del comportamiento y uso de clientes de telecomunicaciones

📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en Latinoamérica.

A partir de información de usuarios, planes contratados y registros de uso de llamadas y mensajes, se realizó un proceso completo de limpieza, exploración, análisis estadístico y segmentación de clientes para identificar patrones de consumo, detectar comportamientos atípicos y generar recomendaciones de negocio.

## 🎯 Objetivos

- Analizar el comportamiento de uso de llamadas y mensajes de los clientes.
- Detectar problemas de calidad de los datos y realizar las correcciones necesarias.
- Identificar valores atípicos (outliers) en los patrones de uso.
- Segmentar a los clientes según características como edad y nivel de uso.
- Identificar patrones que puedan apoyar la toma de decisiones comerciales.
- Generar recomendaciones relacionadas con la oferta de planes y estrategias de retención.

## 📁 Conjuntos de datos utilizados

- **planes.csv:** información sobre los planes ofrecidos, incluyendo precio mensual, minutos y GB incluidos y costos por consumo adicional.
- **usuarios_latam.csv:** información de los clientes, como edad, ciudad, fecha de registro y plan contratado.
- **uso.csv:** registros de actividad de los usuarios, incluyendo llamadas y mensajes.

🔎 Etapas del Análisis
1. Carga y Exploración de Datos
Importación de librerías.
Carga de datasets.
Revisión de estructura, dimensiones y tipos de datos.
2. Calidad de Datos
Identificación de valores nulos.
Detección de sentinels e inconsistencias.
Validación de variables categóricas.
Revisión de fechas fuera de rango.
3. Limpieza de Datos
Reemplazo del valor sentinel -999 en edad.
Sustitución del valor "?" por valores nulos.
Corrección de fechas futuras.
Validación de nulos dependientes del tipo de registro.
4. Análisis Estadístico
Estadísticas descriptivas.
Distribuciones de variables numéricas.
Frecuencias de variables categóricas.
5. Detección de Outliers
Histogramas.
Boxplots.
Método IQR para validación de valores extremos.
6. Segmentación de Clientes
Segmentación por nivel de uso:
Bajo uso
Uso medio
Alto uso
Segmentación por edad:
Joven
Adulto
Adulto Mayor
7. Insights de Negocio
Identificación de segmentos con diferentes niveles de uso.
Análisis de patrones relevantes para el negocio.
Propuestas de posibles acciones comerciales a partir de los resultados observados.

🛠️ Tecnologías Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
GitHub

▶️ Cómo Ejecutar el Proyecto
Opción 1: Google Colab
Descargar el archivo .ipynb.
Abrir Google Colab.
Seleccionar Archivo → Subir Notebook.
Cargar el notebook.
Ejecutar las celdas en orden.
Opción 2: Jupyter Notebook
Clonar el repositorio:
git clone URL_DEL_REPOSITORIO
Entrar al proyecto:
cd telecom-analysis
Instalar dependencias:
pip install pandas numpy matplotlib seaborn jupyter
Ejecutar:
jupyter notebook
Abrir el notebook principal y ejecutar todas las celdas.

🔄 Guía de Reproducción
Descargar o clonar este repositorio.
Colocar los archivos:
plans.csv
users_latam.csv
usage.csv
Abrir el notebook.
Ejecutar las celdas en orden desde el inicio.
Revisar las visualizaciones, estadísticas y conclusiones generadas.

## 💡 Principales hallazgos

El análisis permitió identificar diferencias en los patrones de uso entre los clientes, así como valores atípicos y segmentos con distintos niveles de consumo.

La segmentación por edad y nivel de uso permitió describir grupos de clientes con comportamientos diferentes, proporcionando información que puede utilizarse como apoyo para futuras decisiones comerciales.

## 👩‍💻 Autora

**Denisse Ungson**  
Analista de Datos Junior
