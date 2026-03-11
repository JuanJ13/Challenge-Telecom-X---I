#**Análisis de Evasión de Clientes (Churn) - Telecom X**


**1. Descripción del Proyecto**
Este proyecto analiza el comportamiento y la retención de clientes de la operadora Telecom X, con el objetivo de identificar los patrones que motivan la cancelación de servicios (Churn). A través de técnicas de análisis de datos con Pandas y Matplotlib/Seaborn, evaluamos variables críticas como el tipo de contrato, la antigüedad (tenure), la calidad del servicio de internet y los métodos de pago para proponer estrategias de retención efectivas.

**2. Metodología de Análisis**
El análisis siguió el ciclo de vida estándar de ciencia de datos:

**Consolidación y Normalización:** Integración y limpieza de datasets con diccionarios anidados para obtener datos tabulares estructurados.

**Limpieza y Procesamiento:** Uso de técnicas de filtrado, manejo de valores faltantes (imputación a N/A) y creación de nuevas métricas (como Cuentas_Diarias).

**Exploración Estadística:** Identificación de patrones mediante diagramas de caja (Boxplots) y gráficos de densidad (KDE Plots) para comparar clientes que se van frente a los que permanecen.

**Visualización:** Implementación de gráficos de barras comparativos para segmentación categórica y análisis de correlación.

**3. Principales Hallazgos**
**Vulnerabilidad Inicial:** Identificamos que los clientes que desisten del servicio tienen, en promedio, menos de 10 meses de permanencia, lo que marca una etapa crítica de riesgo.

**Brecha en Pagos:** Existe una correlación significativa entre el uso de pagos electrónicos y la tasa de abandono, con más de 1,000 casos detectados.

**Problemas Técnicos:** El servicio de fibra óptica presenta la mayor tasa de deserción (más de 1,250 clientes), sugiriendo posibles fallas en la calidad o satisfacción del servicio técnico.

**4. Conclusión y Recomendación**
Tras el análisis integral, concluimos que la evasión no es aleatoria, sino que está concentrada en los primeros meses de relación contractual y en servicios/métodos específicos. Se recomienda a la gerencia:

Realizar una auditoría técnica profunda sobre la calidad de la fibra óptica.

Optimizar la experiencia de usuario en los pagos digitales.

Implementar un programa de fidelización proactivo durante los primeros 10 meses de contrato para aumentar el tenure promedio y garantizar la sostenibilidad del negocio.

**5. Tecnologías Utilizadas**

**Lenguaje:** Python 3.x

**Librerías:**

**- Pandas:** Manipulación, normalización y análisis de datos.

**- Matplotlib / Seaborn**: Visualización avanzada de datos y creación de gráficos estadísticos.

Pandas: Manipulación, normalización y análisis de datos.

Matplotlib / Seaborn: Visualización avanzada de datos y creación de gráficos estadísticos.
