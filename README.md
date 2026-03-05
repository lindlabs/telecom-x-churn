# Informe de Ingenieria y Analisis de Datos: Telecom X Churn

## Introduccion
Este proyecto documenta el desarrollo de un pipeline de datos para identificar los factores determinantes en la perdida de clientes de la empresa Telecom X. El analisis integra procesos de extraccion, transformacion y modelado estadistico para generar inteligencia de negocio accionable.

## Metodologia y Procesamiento de Datos
El flujo de trabajo se implemento bajo los siguientes estandares tecnicos:
* Extraccion y Normalizacion: Conexion a la interfaz de datos y aplanamiento de estructuras JSON para su conversion a DataFrames de Pandas.
* Depuracion de Datos: Eliminacion de registros con valores nulos y duplicados, resultando en una muestra final de 7,032 usuarios validos.
* Estandarizacion de Variables: Traduccion tecnica de columnas al espanol y normalizacion de cadenas de texto.
* Codificacion de Atributos: Transformacion de variables categoricas a formato binario para facilitar el procesamiento matematico.
* Ingenieria de Caracteristicas: Implementacion de la metrica Costo_Diario para evaluar el impacto economico prorrateado por usuario.

## Hallazgos Estadisticos Relevantes
* Tasa de Evasion: Se identifico una desercion del 26.6% en el periodo analizado.
* Analisis Contractual: Los usuarios con contratos de renovacion mensual presentan la mayor volatilidad, en contraste con la estabilidad de los contratos a largo plazo.
* Comportamiento Financiero: El uso de cheque electronico como metodo de pago esta correlacionado con una mayor probabilidad de abandono.
* Correlacion de Permanencia: La antiguedad del cliente presenta una correlacion negativa de -0.35 respecto a la evasion, consolidandose como el principal factor de retencion.

## Recomendaciones Tecnicas y Estrategicas
* Implementar protocolos de fidelizacion intensiva para clientes en sus primeros 12 meses de servicio.
* Disenar incentivos para la migracion de usuarios hacia metodos de pago automatizados.
* Desarrollar ofertas competitivas dirigidas a segmentos con cargos mensuales elevados para mitigar la sensibilidad al precio.

## Requisitos del Entorno
* Python 3.x
* Bibliotecas: Pandas, Matplotlib, Seaborn
* Ejecucion: El analisis se encuentra documentado en formato .ipynb para su reproduccion en entornos de computacion interactiva.
