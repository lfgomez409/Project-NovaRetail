📊 Análisis de Comportamiento de Clientes en NovaRetail+
Descripción del proyecto

Este proyecto analiza los factores de comportamiento de los clientes que están más relacionados con los ingresos anuales generados para NovaRetail+, una plataforma de comercio electrónico con presencia en Latinoamérica.

El análisis se desarrolló utilizando técnicas estadísticas de correlación, visualización de datos y análisis exploratorio para identificar patrones de comportamiento que puedan aportar información valiosa a los equipos de crecimiento y retención. El objetivo no fue establecer relaciones causales, sino descubrir asociaciones significativas que ayuden a comprender mejor qué características y acciones de los clientes están vinculadas con una mayor generación de ingresos.

Objetivo de negocio

El equipo de Crecimiento y Retención de NovaRetail+ buscaba responder una pregunta clave:

¿Qué factores del comportamiento de los clientes están más fuertemente asociados con los ingresos anuales generados para la empresa?

Responder esta pregunta permite identificar oportunidades para mejorar estrategias de retención, segmentación, fidelización y optimización de inversiones en marketing.

Objetivos del análisis
Explorar el comportamiento de los clientes mediante análisis descriptivos.
Identificar relaciones significativas entre variables de comportamiento e ingresos.
Aplicar diferentes métodos de correlación según el tipo de variable analizada.
Detectar correlaciones potencialmente engañosas o mal interpretadas.
Documentar supuestos, limitaciones y alcances del análisis.
Transformar los hallazgos en recomendaciones de negocio accionables.
Dataset

El conjunto de datos contiene información de 15.000 clientes y combina variables demográficas, de comportamiento, satisfacción y valor económico.

Variables incluidas
Variable	Descripciónid_cliente	Identificador único del cliente
edad	Edad del cliente
nivel_ingreso	Ingreso anual estimado del cliente
visitas_mes	Número de visitas mensuales a la plataforma
compras_mes	Número de compras realizadas por mes
gasto_publicidad_dirigida	Inversión publicitaria asociada al cliente
satisfaccion	Calificación de satisfacción del cliente (1-5)
miembro_premium	Indica si el cliente posee suscripción premium
abandono	Indica si el cliente abandonó la plataforma
tipo_dispositivo	Dispositivo principal utilizado
region	Región geográfica del cliente
ingreso_anual	Ingreso anual generado para la empresa
Variable objetivo

ingreso_anual

Esta variable representa el valor económico generado por cada cliente y constituye el foco principal del análisis.

Tecnologías utilizadas
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Metodología
1. Exploración inicial de datos

Se realizó una inspección general del conjunto de datos para comprender:

Estructura del dataset.
Tipos de datos.
Estadísticas descriptivas.
Calidad y consistencia de la información.
2. Preparación de datos

Durante esta etapa se llevaron a cabo tareas de:

Validación de variables.
Revisión de valores faltantes.
Definición de supuestos de análisis.
Selección de variables relevantes.
3. Análisis exploratorio y visualización

Se utilizaron diferentes técnicas visuales para identificar patrones y relaciones potenciales:

Heatmaps de correlación.
Scatterplots.
Distribuciones de variables.
Comparaciones entre segmentos de clientes.
4. Análisis de correlación

Debido a la naturaleza diversa de las variables, se aplicaron diferentes métodos estadísticos:

Correlación de Pearson

Utilizada para medir relaciones lineales entre variables numéricas.

Correlación de Spearman

Aplicada para detectar relaciones monotónicas cuando los datos no cumplen supuestos de normalidad o linealidad.

Correlación Punto-Biserial

Utilizada para analizar relaciones entre variables binarias y variables numéricas continuas.

V de Cramér

Aplicada para evaluar la fuerza de asociación entre variables categóricas.

5. Interpretación de resultados

Los hallazgos fueron evaluados bajo el siguiente enfoque:

Evidencia estadística → Interpretación responsable → Implicación de negocio

En todo momento se evitó inferir causalidad a partir de correlaciones observadas.

Preguntas de investigación

Durante el análisis se exploraron preguntas como:

¿Existe relación entre la frecuencia de compra y los ingresos generados?
¿La satisfacción del cliente está asociada con un mayor valor económico?
¿Los clientes premium generan más ingresos que los no premium?
¿El abandono afecta significativamente los ingresos?
¿Existen diferencias relevantes según la región o el dispositivo utilizado?
Limitaciones del estudio
El análisis es exclusivamente correlacional.
Las correlaciones encontradas no implican relaciones de causa y efecto.
Pueden existir variables externas no incluidas en el dataset que influyan en los resultados.
Los hallazgos deben validarse mediante experimentación o análisis complementarios antes de tomar decisiones estratégicas.
Valor para el negocio

Los resultados de este proyecto pueden ayudar a NovaRetail+ a:

Identificar comportamientos asociados con clientes de alto valor.
Diseñar estrategias más efectivas de retención.
Optimizar campañas de marketing y asignación de recursos.
Mejorar iniciativas de fidelización y suscripciones premium.
Priorizar futuras investigaciones y experimentos orientados al crecimiento.
Estructura del repositorio
Plain Text
Project-NovaRetail/
│
├── data/
│ └── novaretail_comportamiento_clientes_2024.csv
│
├── notebooks/
│ └── NovaRetail_Analysis.ipynb
│
├── images/
│ ├── heatmap.png
│ ├── scatterplot_1.png
│ └── scatterplot_2.png
│
├── README.md
└── requirements.txt
Resultados esperados

El producto final consiste en un análisis exploratorio y correlacional completamente documentado que combina evidencia visual y estadística para comprender mejor los factores asociados al valor económico generado por los clientes de NovaRetail+. Los hallazgos obtenidos sirven como base para futuras estrategias de crecimiento, retención y experimentación basada en datos.

Autor

Luis Felipe Gómez Contreras
 Proyecto desarrollado como parte del programa Data Analyst de TripleTen.
