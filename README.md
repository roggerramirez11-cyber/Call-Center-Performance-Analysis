Descripción general

Este proyecto analiza el desempeño operativo de un call center a partir de datos históricos de llamadas.
El objetivo es evaluar la eficiencia de los agentes, identificar diferencias de desempeño y generar insights accionables que permitan mejorar la gestión de llamadas y la experiencia del cliente.

El análisis se desarrolló utilizando SQL para el modelado y procesamiento de datos, y Power BI para la visualización y comunicación de resultados, siguiendo un flujo de trabajo utilizado en entornos reales de negocio.

 Preguntas de negocio

El proyecto se enfoca en responder las siguientes preguntas clave:

¿Qué tan eficiente es el call center en la atención de llamadas entrantes?

¿Cómo varía el desempeño de los agentes en términos de volumen, tiempo de respuesta y resolución?

¿Qué agentes pierden más llamadas (no contestadas o no resueltas) y dónde existen oportunidades de mejora?

🛠️ Herramientas y tecnologías

SQL (MySQL)

Exploración de datos

Agregaciones

Creación de vistas reutilizables

Power BI

Modelado de datos

Medidas DAX

Dashboards interactivos

GitHub

Documentación y portafolio

 KPIs analizados

Durante el análisis se definieron y evaluaron los siguientes indicadores clave:

Total de llamadas

Answered Rate (porcentaje de llamadas contestadas)

Resolution Rate (porcentaje de llamadas resueltas)

Tiempo promedio de respuesta

Duración promedio de las llamadas

Efectividad del agente (métrica personalizada)

Estos KPIs se presentan de forma destacada en el dashboard para ofrecer una visión rápida del desempeño general.

Dashboard

El dashboard en Power BI incluye:

KPIs generales para evaluar el estado del call center

Comparación de desempeño por agente, considerando volumen de llamadas y tiempo promedio de respuesta

Tabla de efectividad de agentes con formato condicional para identificar fácilmente alto y bajo desempeño

Página de insights, donde se resumen los principales hallazgos y recomendaciones



🔍 Principales insights

Aproximadamente el 19% de las llamadas no son contestadas, lo que representa una oportunidad importante de mejora en la atención al cliente.

Una vez que la llamada es contestada, el porcentaje de resolución es alto (~90%), lo que indica que el principal problema ocurre antes de la atención.

Existen diferencias claras de desempeño entre agentes, incluso entre aquellos con volúmenes similares de llamadas.

Algunos agentes mantienen una alta efectividad de forma consistente, lo que sugiere buenas prácticas que podrían replicarse en el resto del equipo.

 Recomendaciones

A partir de los resultados del análisis, se sugieren las siguientes acciones:

Identificar y replicar las prácticas de los agentes con mayor efectividad.

Priorizar capacitación o ajustes de carga de trabajo para agentes con alto número de llamadas no contestadas o no resueltas.

Monitorear de forma periódica los KPIs clave mediante el dashboard.

Ampliar el análisis en futuras iteraciones incorporando variables como el tema de la llamada o la satisfacción del cliente.
