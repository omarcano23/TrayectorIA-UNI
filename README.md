# Transformando-la-Educaci-n-Superior-con-IA
Este proyecto tiene como objetivo desarrollar un sistema de trazabilidad para monitorizar y analizar el desempeño académico de los estudiantes desde su admisión hasta su graduación. Usando técnicas de análisis de datos y modelos predictivos, el proyecto busca identificar factores críticos que influyen en el éxito o el abandono académico, permitiendo la implementación de intervenciones tempranas y efectivas.

Descripción de Carpetas Principales

- 01_Diagnostico_Preparacion: Contiene los pasos iniciales del proyecto, incluyendo la configuración del entorno, análisis descriptivo, limpieza de datos, y análisis de clusterización.

  - Configuracion_Entorno: Instrucciones para configurar el entorno de desarrollo en Visual Studio Code (VSC) usando Python.
  - Descripcion_Desercion: Notebooks y visualizaciones iniciales para entender las características de la deserción.
  - Limpieza_Datos: Procesos de limpieza y transformación de los datos.
  - Clusterizacion: Análisis de clusterización para segmentar estudiantes en grupos homogéneos.

- 02_Modelos_Predictivos: Incluye el desarrollo, validación y generación de predicciones mediante modelos de machine learning.

  - Desarrollo_Modelos: Notebooks para el desarrollo de modelos como regresión logística y árboles de decisión.
  - Validacion_Modelos: Evaluación de los modelos usando métricas como precisión, recall y F1-score.
  - Predicciones: Generación de predicciones y priorización de intervenciones.

- 03_Visualizacion_Comunicacion: Dedicado a la visualización de los resultados en Power BI y la creación del informe final.

  - PowerBI: Archivos de configuración y dashboards interactivos en Power BI.
  - Informe_Final: Informe final del proyecto en PDF y presentación de resultados.
  - Publicaciones: Archivos relacionados con la publicación en plataformas requeridas.

- 04_Documentacion_Administrativa: Documentos administrativos como la propuesta inicial, cronograma del proyecto y actas de reuniones.

- 05_Datos: Almacena los datos utilizados en el proyecto.

  - Datos_Crudos: Archivos de datos originales sin procesar.
  - Datos_Procesados: Archivos de datos después de la limpieza y transformación.

- 06_Scripts_Utilidades: Scripts de Python para análisis de datos, modelos predictivos y visualización.

  - Analisis_Datos: Scripts para el análisis descriptivo y de clusterización.
  - Modelos_Predictivos: Scripts para la implementación de modelos de machine learning.
  - Visualizaciones: Scripts para la integración de resultados en Power BI.

Requisitos Previos

- Herramientas Necesarias
  Visual Studio Code (VSC): Editor de código recomendado.
  Python 3.x: Lenguaje de programación utilizado para el análisis y modelado de datos.
  Bibliotecas de Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, entre otras.
  Power BI: Herramienta para la creación de visualizaciones interactivas.

- Instalación de Bibliotecas
  Para instalar las bibliotecas necesarias, ejecuta el siguiente comando en tu terminal:
  pip install -r requirements.txt

Instrucciones de Uso

- Configuración del Entorno

1. Clona este repositorio en tu máquina local.
2. Instala las bibliotecas requeridas usando el comando mencionado anteriormente.
3. Abre el proyecto en Visual Studio Code.

- Ejecución del Proyecto

1. Sigue los pasos en los notebooks dentro de la carpeta 01_Diagnostico_Preparacion para el análisis descriptivo y la limpieza de datos.
2. Desarrolla y valida los modelos predictivos utilizando los notebooks en 02_Modelos_Predictivos.
3. Conecta el proyecto a Power BI y crea visualizaciones interactivas siguiendo las instrucciones en 03_Visualizacion_Comunicacion.
4. Genera el informe final y publica los resultados en las plataformas requeridas.

Contribuciones
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu característica (git checkout -b feature/nueva-caracteristica).
3. Haz commit de tus cambios (git commit -am 'Agrega nueva característica').
4. Haz push a la rama (git push origin feature/nueva-caracteristica).
5. Crea un Pull Request.

Contacto
Para cualquier duda o sugerencia, por favor contacta a [tu nombre o equipo] en [tu correo electrónico].
