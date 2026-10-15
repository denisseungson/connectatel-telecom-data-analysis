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

## 🔎 Etapas del Análisis

1. **Carga y Exploración de Datos**
   - Importación de librerías.
   - Carga de conjuntos de datos.
   - Revisión de estructura, dimensiones y tipos de datos.

2. **Calidad de Datos**
   - Identificación de valores nulos.
   - Detección de centinelas e inconsistencias.
   - Validación de variables categóricas.
   - Revisión de fechas fuera de rango.

3. **Limpieza de Datos**
   - Reemplazo del valor sentinel -999 en edad.
   - Sustitución del valor "?" por valores nulos.
   - Corrección de fechas futuras.
   - Validación de nulos dependientes del tipo de registro.

4. **Análisis Estadístico**
   - Estadísticas descriptivas.
   - Distribuciones de variables numéricas.
   - Frecuencias de variables categóricas.

5. **Detección de Outliers**
   - Histogramas.
   - Diagramas de caja.
   - Método IQR para validación de valores extremos.

6. **Segmentación de Clientes**
   - Segmentación por nivel de uso: bajo, medio y alto.
   - Segmentación por edad: joven, adulto y adulto mayor.

7. **Insights de Negocio**
   - Identificación de segmentos con diferentes niveles de uso.
   - Análisis de patrones relevantes para el negocio.
   - Propuestas de posibles acciones comerciales a partir de los resultados observados.
     
## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

## ▶️ Cómo Ejecutar el Proyecto

### Opción 1: Google Colab

1. Descargar el archivo `.ipynb`.
2. Abrir Google Colab.
3. Seleccionar **Archivo → Subir Notebook**.
4. Cargar el cuaderno.
5. Ejecutar las celdas en orden.

### Opción 2: Jupyter Notebook

1. Clonar el repositorio.
2. Entrar al proyecto.
3. Instalar las dependencias.
4. Ejecutar Jupyter Notebook.
5. Abrir el notebook principal y ejecutar todas las celdas.

## 🔄 Guía de Reproducción

1. Descargar o clonar este repositorio.
2. Colocar los archivos:
   - `planes.csv`
   - `usuarios_latam.csv`
   - `uso.csv`
3. Abrir el cuaderno.
4. Ejecutar las celdas en orden desde el inicio.
5. Revisar las visualizaciones, estadísticas y conclusiones generadas.

## 💡 Principales hallazgos

El análisis permitió identificar diferencias en los patrones de uso entre los clientes, así como valores atípicos y segmentos con distintos niveles de consumo.

La segmentación por edad y nivel de uso permitió describir grupos de clientes con comportamientos diferentes, proporcionando información que puede utilizarse como apoyo para futuras decisiones comerciales.

## 👩‍💻 Autora

**Denisse Ungson**  
Analista de Datos Junior
