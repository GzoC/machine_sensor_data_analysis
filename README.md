# Análisis de Datos de Sensores de una Máquina Simple

## Descripción del Proyecto
Este proyecto tiene como objetivo explorar datos simulados de sensores industriales, identificar patrones y posibles anomalías, y visualizar tendencias en series temporales. Es una introducción práctica al análisis de datos para familiarizarse con herramientas como Python, Pandas, Matplotlib y Seaborn.

## Contenido del Proyecto
El proyecto se organiza en las siguientes secciones principales:

1. **Carga y Exploración de Datos:** Se cargan los datos simulados desde un archivo CSV y se realiza una inspección inicial.
2. **Limpieza y Preparación de los Datos:** Se verifican y corrigen valores nulos, además de ajustar formatos de fecha.
3. **Visualización de Datos:** Se crean gráficos de línea para las series temporales de temperatura, presión y vibración.
4. **Análisis Descriptivo y Anomalías:** Estadísticas descriptivas y detección de posibles anomalías mediante técnicas simples como media móvil.
5. **Resultados:** Documentación de los hallazgos y observaciones.

## Estructura de Carpetas
machine_sensor_data_analysis/ 
│ ├── data/ 
│ └── sensor_data.csv # Datos simulados de los sensores 
│ ├── notebooks/ 
│ └── sensor_data_analysis.ipynb # Notebook con el análisis completo 
│ ├── .gitignore # Archivo para ignorar archivos/carpetas innecesarias 
├── requirements.txt # Dependencias del proyecto 
└── README.md # Documentación del proyecto


## Datos
- **Archivo:** `sensor_data.csv`
- **Estructura:**
  - `time_stamp`: Marca de tiempo.
  - `temperature`: Temperatura registrada (°C).
  - `pressure`: Presión registrada (hPa).
  - `vibration`: Vibración registrada (g).

## Instalación
Sigue estos pasos para instalar y ejecutar el proyecto en tu entorno local:

1. **Clonar el repositorio:**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd machine_sensor_data_analysis
2. **Crear y activar un entorno virtual:**
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows

3. **Instalar dependencias:**
    pip install -r requirements.txt

4. **Abrir el Notebook:**
    jupyter notebook notebooks/sensor_data_analysis.ipynb

## Dependencias
    Python: 3.8 o superior
    Librerías:
        pandas
        numpy
        matplotlib
        seaborn
        jupyter

## Uso
    Abre el archivo sensor_data_analysis.ipynb en Jupyter Notebook.
    Ejecuta las celdas para explorar y analizar los datos de sensores.
    Observa los gráficos y las estadísticas descriptivas para interpretar tendencias y anomalías.

## Próximos Pasos
    Implementar modelos de predicción de series temporales.
    Integrar datos reales de sensores para análisis más avanzados.
    Automatizar reportes de tendencias y anomalías.

## Contribuciones
    Siente libre de contribuir al proyecto con nuevas ideas o mejoras.