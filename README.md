# banco-caja
El propósito de este proyecto consiste en desarrollar un modelo matemático que permita identificar con mayor precisión a los solicitantes de crédito que presenten una mayor probabilidad de convertirse en malos pagadores. Este enfoque se basará en análisis estadísticos y algoritmos predictivos con el objetivo de mejorar la eficacia en la evaluación de riesgos crediticios, contribuyendo así a la toma de decisiones más informada y al mantenimiento de la salud financiera de la institución crediticia.

# Contexto
En el actual contexto, la reducción de tasas de interés ha impulsado una significativa demanda de créditos, generando un aumento en las solicitudes en el banco "Super Caja". El equipo de análisis de crédito se enfrenta a una carga de trabajo abrumadora debido a la metodología manual actual, lo que resulta en un proceso ineficiente y demorado. La creciente preocupación por la tasa de incumplimiento añade presión para mitigar riesgos.

La propuesta para abordar este desafío consiste en la automatización del proceso de análisis mediante técnicas avanzadas de análisis de datos. El objetivo es mejorar la eficiencia, precisión y rapidez en la evaluación de las solicitudes de crédito. Además, se sugiere integrar la métrica existente que identifica a clientes con pagos atrasados en el nuevo sistema automatizado para fortalecer la clasificación de riesgo.


#Para lograr el objetivo, se utilizó la técnica del riesgo relativo.
Se empleó la técnica de riesgo relativo para calcular la probabilidad asociada a la calidad crediticia de un usuario, siendo esta una medida estadística comúnmente utilizada en epidemiología y otras áreas. Este método evalúa la relación entre la exposición a un factor de riesgo específico y la manifestación de un resultado particular, análogo a la asociación entre un evento adverso y una enfermedad. El riesgo relativo se determina como la proporción de la incidencia del resultado en el grupo expuesto al factor de riesgo en comparación con el grupo no expuesto.

En resumen, el riesgo relativo proporciona una indicación cuantitativa de la probabilidad relativa de que ocurra un resultado entre el grupo expuesto en comparación con el grupo no expuesto. Un riesgo relativo igual a 1 implica ausencia de diferencia en la incidencia entre ambos grupos. Si el riesgo relativo es mayor que 1, señala un mayor riesgo en el grupo expuesto, mientras que un valor menor que 1 indica un menor riesgo en dicho grupo. Este enfoque permite evaluar la asociación entre la exposición al factor de riesgo y la probabilidad de ser buen o mal pagador.


# Herramientas usadas
✅Google BigQuery: Almacén de datos que permite el procesamiento de grandes volúmenes de datos.
✅Google Colab: Plataforma para trabajar con Python en Notebooks
✅Google Looker Studio: Herramienta para la creación y edición de dashboards, informes de datos.
# Lenguajes
✅SQL en BigQuery y Python en Google Colab.
