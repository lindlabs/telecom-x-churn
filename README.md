#  Telecom X: Estrategias de Retención de Clientes (Churn Analysis)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4479A1?style=for-the-badge&logo=python)

Este proyecto aplica técnicas avanzadas de **Data Science** para desglosar el comportamiento de abandono (Churn) en una empresa de telecomunicaciones. El objetivo central es transformar datos crudos en inteligencia de negocio para reducir la pérdida de clientes.

---

##  Pipeline de Datos
El proyecto sigue un flujo de trabajo profesional dividido en cinco fases críticas:

1. ETL & Normalización: Conexión a API corporativa, aplanamiento de estructuras JSON complejas y tratamiento riguroso de valores nulos.
2. Transformación Semántica: Traducción integral del dataset al español y estandarización de categorías.
3. Feature Engineering: Creación de métricas de valor como `Costo_Diario` y `Total_Servicios` para medir la densidad del contrato.
4. EDA (Análisis Exploratorio): Identificación visual de patrones demográficos y contractuales que detonan la fuga.
5. Análisis Estadístico: Implementación de matrices de correlación para validar hipótesis de negocio.

---

##  Hallazgos Clave (Insights)

| Métrica | Resultado | Impacto |
| :--- | :--- | :--- |
| **Tasa de Evasión** | **26.6%** | Nivel crítico que requiere intervención inmediata. |
| **Contratos Críticos** | Mes a Mes | Los contratos cortos concentran la mayor volatilidad. |
| **Factor de Retención** | Antigüedad | A mayor permanencia (30+ meses), el riesgo de fuga cae drásticamente. |
| **Correlación** | -0.35 | La permanencia es el predictor negativo más fuerte de evasión. |

---

##  Recomendaciones Estratégicas

Basado en la evidencia de los datos, se proponen tres ejes de acción:

*  Blindaje de Clientes Nuevos: Implementar programas de éxito del cliente durante los primeros 12 meses, detectado como el periodo de mayor riesgo.
*  Optimización de Cobranza: Incentivar la migración de **Cheque Electrónico** a métodos automáticos, reduciendo la fricción en el pago que genera Churn.
*  Gestión de Precios: Revisar la competitividad de planes con cargos mensuales elevados, ya que presentan una correlación directa con la pérdida de clientes.

---

##  Configuración del Entorno

1. **Clonación**: `git clone https://github.com/lindlabs/telecom-x-churn.git`
2. **Dependencias**: `pip install pandas matplotlib seaborn`
3. **Ejecución**: Abrir `TelecomX_Churn_Analysis.ipynb` en **Google Colab** o Jupyter Notebook.

---

Desarrollado con fines analíticos para el portafolio de **Lindlabs**.
