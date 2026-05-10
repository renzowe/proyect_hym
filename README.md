Proyecto H&M – Análisis de Ventas con Lakehouse y Power BI
 Descripción del proyecto

    Este proyecto tiene como objetivo analizar datos de ventas del sector retail mediante un enfoque Lakehouse, utilizando Python
    para la transformación de datos y Power BI para la visualización y análisis de negocio.
    Se trabajó con grandes volúmenes de datos en formato Parquet, los cuales fueron procesados, modelados 
    y utilizados para construir indicadores clave de rendimiento (KPIs), análisis de clientes y dashboards analíticos.

    Tecnologías utilizadas
        Python (Pandas)
        Parquet
        Power BI
        Git y GitHub
        Google Drive (almacenamiento de datos)
    Arquitectura del flujo de datos

 El proyecto sigue el siguiente flujo:

    Datos de origen (Lakehouse)
    → Procesamiento y limpieza en Python (Notebooks)
    → Generación de datasets en formato Parquet optimizado
    → Modelado en Power BI
    → Desarrollo de dashboards analíticos
    Estructura del repositorio
    proyecto_hym/
    │
    ├── notebooks/        # Procesamiento y análisis en Python
    ├── data_sample/      # Muestra reducida del dataset
    ├── reportes/         # Imágenes de dashboards
    ├── README.md         # Documentación
     Data completa y Power BI

 Debido al tamaño del dataset y del archivo de Power BI, estos no se incluyen en el repositorio.

    Acceso a la data completa (Lakehouse + PBIX):
    https://drive.google.com/drive/folders/1N7LC2aiJamj_XmpBDEPkiAIfVw6cank2?usp=sharing

 Data sample

    Se incluye una muestra reducida del dataset en la carpeta data_sample/, lo que permite reproducir parte del análisis sin necesidad de descargar toda la data.

 Resultados analíticos

    Se desarrollaron distintos módulos de análisis que cubren el ciclo completo del comportamiento del cliente y el rendimiento del negocio.

 Análisis Exploratorio de Datos (EDA)

    Permite entender la distribución de ventas, clientes y productos, así como detectar patrones iniciales.

 Análisis de ventas y forecast

    Incluye proyecciones de ventas basadas en tendencias históricas.

 Segmentación ABC / XYZ

    Permite clasificar:

    ABC: según volumen de ventas
    XYZ: según variabilidad de la demanda

 Forecast – Segmento BX

 Forecast – Segmento AY

 Segmentación de clientes
 Segmentación LRFM

    Clasifica a los clientes según:

    Recency (recencia)
    Frequency (frecuencia)
    Monetary (valor monetario)
    Length (Tiempo del cliente)



 Análisis de cohortes

    Evalúa la retención de clientes a lo largo del tiempo.

 Análisis de churn

    Identifica clientes con alta probabilidad de abandono.

 Conclusiones
    Se logró implementar una arquitectura tipo Lakehouse eficiente para el procesamiento de grandes volúmenes de datos.
    La segmentación de clientes permite identificar oportunidades de negocio y estrategias de fidelización.
    Los modelos de forecast ayudan a anticipar la demanda y mejorar la toma de decisiones.
    El uso de Power BI facilita la interpretación de datos mediante dashboards interactivos.
