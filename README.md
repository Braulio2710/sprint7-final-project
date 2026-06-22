📊 Análisis de Segmentación de Clientes


🎯 Objetivo del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes a partir de su uso del servicio (llamadas y mensajes), con el fin de:

Identificar patrones de consumo
Segmentar usuarios según nivel de uso y edad
Detectar posibles comportamientos atípicos
Generar insights útiles para decisiones de negocio
📁 Datasets utilizados

El análisis se realizó utilizando un dataset de usuarios con las siguientes variables principales:

age: edad del usuario
cant_llamadas: número de llamadas realizadas
cant_mensajes: número de mensajes enviados
cant_minutos_llamada: minutos totales de llamadas

Además, se construyó un dataset enriquecido (user_profile) con variables derivadas como:

grupo_uso (Bajo uso, Uso medio, Alto uso)
grupo_edad (Joven, Adulto, Adulto Mayor)
🔍 Etapas del análisis

El proyecto se desarrolló en las siguientes fases:

1. Exploración de datos (EDA)
Identificación de valores nulos
Revisión de estadísticos descriptivos (describe)
Análisis de distribución de variables
2. Detección de valores atípicos
Uso del método IQR
Identificación de posibles outliers en:
llamadas
mensajes
minutos de llamada
3. Segmentación de clientes
Creación de variables categóricas:
grupo_uso
grupo_edad
Clasificación basada en reglas de negocio
4. Análisis de segmentación
Cruce entre variables categóricas
Tablas de contingencia
Análisis de comportamiento por grupo
5. Visualización de datos
Gráficos de distribución con countplot
Análisis visual de segmentos de clientes
▶️ Cómo ejecutar el proyecto

Puedes ejecutar este proyecto de las siguientes formas:

📌 Opción 1: Google Colab (recomendado)
Abre Google Colab: https://colab.research.google.com/
Sube el archivo .ipynb
Ejecuta las celdas en orden
📌 Opción 2: Jupyter Notebook local
Instala dependencias:
pip install pandas numpy matplotlib seaborn
Abre Jupyter:
jupyter notebook
Abre el archivo .ipynb y ejecuta las celdas
🔁 Guía de reproducción

Para reproducir el análisis correctamente:

Cargar el dataset original en un DataFrame (user_profile)
Ejecutar limpieza y validación de datos
Generar variables derivadas (grupo_uso, grupo_edad)
Realizar análisis descriptivo
Construir visualizaciones
Interpretar resultados por segmento
📌 Resultados clave
El segmento Adulto presenta mayor nivel de uso del servicio
El grupo de Uso medio domina en todos los rangos de edad
Existen diferencias claras de comportamiento entre edades
Se identifican oportunidades de segmentación para estrategias de negocio
🛠️ Tecnologías utilizadas
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook / Google Colab
📈 Posibles mejoras futuras
Modelos predictivos de churn
Segmentación avanzada con clustering (K-Means)
Análisis de valor de cliente (CLV)
Dashboards interactivos (Power BI o Tableau)
