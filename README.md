# AB_testing_landing_page

**1. Descripción del proyecto**

Este proyecto consiste en el análisis de un experimento A/B cuyo objetivo es evaluar el desempeño de dos versiones de una página de aterrizaje (Landing Page), identificadas como versión A y versión B.

A través del análisis exploratorio de datos y la aplicación de pruebas estadísticas, se busca identificar diferencias en el comportamiento de los usuarios, especialmente en términos de conversión y gasto promedio, para determinar cuál de las dos versiones presenta mejores resultados.

El proyecto hace parte de mi formación práctica como Data Analyst en el bootcamp de TripleTen.

**2. Objetivos del análisis**

Comparar las tasas de conversión de las versiones A y B.

Evaluar si existen diferencias estadísticamente significativas en el comportamiento de los usuarios entre ambas versiones.

Analizar la relación entre las fuentes de tráfico y las conversiones.

Explorar el comportamiento del gasto de los usuarios que realizaron una conversión.

Formular conclusiones y recomendaciones basadas en los resultados obtenidos.

**3. Herramientas y tecnologías**

Python: lenguaje principal para el procesamiento y análisis de datos.

Pandas y NumPy: manipulación, limpieza y transformación de datos.

Matplotlib y Seaborn: análisis exploratorio y visualización de datos.

SciPy: aplicación de pruebas estadísticas e inferenciales.

Jupyter Notebook: entorno de desarrollo y documentación del análisis.

**4. Metodología**

El análisis se desarrolló mediante las siguientes etapas:

Exploración y preparación de datos: revisión de la estructura del conjunto de datos, tipos de variables, valores ausentes y consistencia de la información.

Análisis exploratorio (EDA): evaluación de distribuciones, frecuencias y patrones de comportamiento mediante estadísticas descriptivas y visualizaciones.

Análisis de conversión: comparación de las tasas de conversión de las versiones A y B.

Análisis por segmentos: exploración de las conversiones según la fuente de tráfico y el tipo de usuario.

Pruebas estadísticas: aplicación de pruebas de hipótesis para evaluar la significancia de las diferencias observadas.

Conclusiones y recomendaciones: interpretación de los resultados desde una perspectiva de negocio.

**5. Principales hallazgos**

Comparación de tasas de conversión

La versión A registró una tasa de conversión aproximada del 12.57 %.

La versión B alcanzó una tasa de conversión aproximada del 15.96 %.

La diferencia fue de aproximadamente 3.38 puntos porcentuales a favor de la versión B.

La prueba estadística arrojó un valor p de aproximadamente 3.76 × 10⁻²², proporcionando evidencia estadística suficiente para identificar una diferencia entre ambas versiones.

Comportamiento del gasto

Al analizar únicamente a los usuarios que realizaron una conversión, se observaron los siguientes resultados:

Gasto promedio en la versión A: 61.09.

Gasto promedio en la versión B: 68.75.

Diferencia aproximada: 12.54 % a favor de la versión B.

La prueba t de Welch identificó una diferencia estadísticamente significativa entre los promedios de gasto de ambos grupos.

Análisis de fuentes de tráfico

Se identificó una asociación estadísticamente significativa entre la fuente de tráfico y la conversión (p ≈ 0.0341).

Entre los resultados descriptivos se destacan:

Email: tasa de conversión aproximada del 14.99 %.

Ads: tasa de conversión aproximada del 14.74 %.

Organic: tasa de conversión aproximada del 13.79 %.

Referral: tasa de conversión aproximada del 13.88 %.

Análisis por tipo de usuario

No se encontró evidencia estadística suficiente para establecer una asociación entre el tipo de usuario y la conversión (p > 0.05).

**6. Conclusiones y recomendaciones**

Los resultados del experimento muestran un mejor desempeño de la versión B frente a la versión A, tanto en términos de tasa de conversión como de gasto promedio entre los usuarios convertidos.

A partir de estos resultados, se plantean las siguientes recomendaciones:

Priorizar la versión B: considerar su implementación debido a su mejor desempeño en conversión.

Optimizar las fuentes de tráfico: profundizar en el análisis de los canales de adquisición, considerando tanto sus tasas de conversión como el volumen de usuarios y los costos asociados.

Monitorear el comportamiento de los usuarios: continuar evaluando los indicadores de conversión y gasto para identificar posibles cambios en el desempeño.

Complementar el análisis financiero: evaluar ingresos por usuario expuesto, costos de adquisición y retorno de inversión (ROI) antes de tomar decisiones definitivas de asignación presupuestaria.

Es importante considerar que una diferencia estadísticamente significativa no implica necesariamente una mayor rentabilidad. Para confirmar el impacto económico de la versión B, sería necesario complementar los resultados con información de costos e ingresos por usuario.
