# Analisis de Evasión de Clientes - Telecom X

Este proyecto consiste en un analisis de datos orientado a identificar los factores principales que impulsan la perdida de clientes (Churn) en la empresa Telecom X. El trabajo incluye la implementacion de procesos de extraccion de datos, limpieza y visualizacion estadistica.

## Tecnologias utilizadas
* Python como lenguaje de programacion principal.
* Pandas para la gestion del proceso ETL (Extraccion, Transformacion y Carga).
* Seaborn y Matplotlib para la generacion de graficos y visualizaciones de datos.

## Hallazgos del analisis
1. Tipo de contrato: Se identifico que el mayor volumen de cancelaciones se concentra en los clientes que mantienen contratos de renovacion mensual (Month-to-month).
2. Costos: Los clientes con cargos mensuales mas altos presentan una tendencia superior a abandonar el servicio en comparacion con los de cargos bajos.
3. Antiguedad: Existe una correlacion negativa entre el tiempo de permanencia y la evasion; los clientes con menos de 6 meses de antiguedad representan el segmento de mayor riesgo.

## Estrategias propuestas
* Desarrollar programas de fidelizacion especificos para clientes nuevos durante su primer semestre de permanencia.
* Implementar campañas de conversion para incentivar la transicion de contratos mensuales a contratos anuales mediante beneficios exclusivos.
* Revisar la estructura de precios para los segmentos de alto costo con el fin de mejorar la percepcion de valor.
