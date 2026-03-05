# Análisis de Evasión de Clientes (Churn) - Telecom X

Este proyecto aplica técnicas de **Ciencia de Datos** para identificar los factores que influyen en la pérdida de clientes en una empresa de telecomunicaciones. El análisis abarca desde la extracción de datos mediante API hasta la generación de insights estratégicos.

##  Estructura del Proyecto
El flujo de trabajo se divide en las siguientes etapas:

1. **Extracción y Limpieza**: Conexión a API, normalización de JSON y tratamiento de valores nulos.
2. **Transformación de Datos**: Traducción de variables al español y conversión de datos categóricos a formato binario (0 y 1).
3. **Ingeniería de Características**: Creación de métricas como `Costo_Diario` y `Total_Servicios`.
4. **Análisis Exploratorio (EDA)**: Visualización de la distribución del Churn y su relación con variables demográficas y contractuales.
5. **Análisis Estadístico**: Cálculo de correlaciones para identificar los predictores más fuertes de evasión.

##  Tecnologías Utilizadas
* **Python 3.x**
* **Pandas**: Manipulación y limpieza de datos.
* **Seaborn & Matplotlib**: Visualización de datos estadística.
* **Google Colab**: Entorno de desarrollo.

##  Hallazgos Principales
* **Tasa de Evasión**: El **26.6%** de los clientes han cancelado el servicio.
* **Riesgo por Contrato**: Los contratos "mes a mes" presentan la mayor fuga, mientras que la antigüedad (Meses de Permanencia) es el factor que más reduce el riesgo de abandono.
* **Impacto Económico**: Existe una relación directa entre cargos mensuales elevados y la probabilidad de evasión.

##  Instalación y Uso
1. Clona este repositorio.
2. Asegúrate de tener instaladas las dependencias: `pip install pandas matplotlib seaborn`.
3. Abre el archivo `.ipynb` en Google Colab o Jupyter Notebook para ejecutar el análisis.

##  Recomendaciones Estratégicas
* Incentivar la migración de contratos mensuales a anuales.
* Implementar programas de fidelización durante los primeros 12 meses de servicio.
* Promover métodos de pago automáticos para reducir la deserción vinculada al cheque electrónico.
