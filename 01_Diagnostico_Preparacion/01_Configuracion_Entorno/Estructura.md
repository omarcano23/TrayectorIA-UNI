Estructura del Proyecto
La estructura del proyecto está organizada de la siguiente manera:

/Py Track Analitico UNI
│
├── /01_Diagnostico_Preparacion
│ ├── /01_Configuracion_Entorno
│ │ └── README.md # Instrucciones de configuración del entorno en VSC y Python
│ ├── /02_Descripcion_Desercion
│ │ ├── Descripcion_Desercion.ipynb # Notebooks para el análisis descriptivo inicial
│ │ └── Visualizaciones # Gráficos y visualizaciones preliminares
│ ├── /03_Limpieza_Datos
│ │ ├── Limpieza_Datos.ipynb # Notebooks para la limpieza de datos
│ │ └── Datos_Limpiados # Archivos de datos limpios
│ └── /04_Clusterizacion
│ ├── Clusterizacion.ipynb # Notebooks para análisis de clusterización
│ └── Resultados_Clusterizacion # Gráficos y resultados del análisis
│
├── /02_Modelos_Predictivos
│ ├── /01_Desarrollo_Modelos
│ │ ├── Regresion_Logistica.ipynb # Notebooks para el modelo de regresión logística
│ │ ├── Arbol_Decision.ipynb # Notebooks para el modelo de árboles de decisión
│ │ └── Modelos_Entrenados # Archivos de modelos entrenados
│ ├── /02_Validacion_Modelos
│ │ ├── Validacion_Modelos.ipynb # Notebooks para la validación y evaluación de modelos
│ │ └── Resultados_Validacion # Métricas y resultados de la validación
│ └── /03_Predicciones
│ ├── Predicciones.ipynb # Notebooks para la generación de predicciones
│ └── Resultados_Predicciones # Archivos con las predicciones generadas
│
├── /03_Visualizacion_Comunicacion
│ ├── /01_PowerBI
│ │ ├── Conexiones_PowerBI # Archivos de configuración de conexión
│ │ ├── Dashboards_PowerBI # Archivos de dashboards de Power BI
│ │ └── Informes_Visualizaciones # Informes y capturas de las visualizaciones
│ ├── /02_Informe_Final
│ │ ├── Informe_Final.pdf # Informe final en PDF
│ │ └── Presentacion_Final # Archivos de la presentación del proyecto
│ └── /03_Publicaciones
│ ├── Publicacion_Plataformas # Archivos relacionados con la publicación en plataformas
│ └── Requisitos_Adicionales # Documentos relacionados con requisitos específicos
│
├── /04_Documentacion_Administrativa
│ ├── Propuesta_Inicial.pdf # Propuesta inicial del proyecto
│ ├── Cronograma_Proyecto.xlsx # Cronograma y plan de trabajo
│ └── Reuniones_Actas # Actas y notas de reuniones
│
├── /05_Datos
│ ├── /01_Datos_Crudos
│ │ └── Datos_Originales # Archivos de datos originales sin procesar
│ └── /02_Datos_Procesados
│ └── Datos_Procesados # Archivos de datos procesados y transformados
│
└── /06_Scripts_Utilidades
├── /01_Analisis_Datos
│ ├── Analisis_Descriptivo.py # Scripts de análisis descriptivo
│ └── Analisis_Clusterizacion.py # Scripts de análisis de clusterización
├── /02_Modelos_Predictivos
│ ├── Regresion_Logistica.py # Script para el modelo de regresión logística
│ └── Arbol_Decision.py # Script para el modelo de árboles de decisión
└── /03_Visualizaciones
└── Visualizacion_PowerBI.py # Script de integración con Power BI
