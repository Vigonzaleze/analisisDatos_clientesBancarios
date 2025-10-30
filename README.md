# Analisis de Datos de Clientes Bancarios
Proyecto que busca realizar variados análisis de los datos obtenidos usando Python

# Tabla de Contenidos
*   [Descripcion](#descripcion)
*   [Resumen Ejecutivo](#resumen-ejecutivo)
*   [Tecnologias y Herramientas Utilizadas](#tecnologias-y-herramientas-utilizadas)
*   [Gráficos Destacados](#gráficos-destacados)
*   [Resultados y Aprendizajes](#resultados-y-aprendizajes)
*   [Estado del Proyecto](#estado-del-proyecto)
*   [Contacto y Enlaces](#contacto-y-enlaces)

# Descripcion
Proyecto orientado a explorar y analizar un conjunto de datos de clientes bancarios con el objetivo de extraer conclusiones descriptivas y detectar patrones relevantes para la toma de decisiones. El análisis principal se encuentra en la carpeta `Analisis` en formato Jupyter Notebook; allí se documentan los pasos de carga de datos, limpieza, análisis exploratorio, visualizaciones y experimentos iniciales de modelado.

# Resumen Ejecutivo
Este proyecto analiza la base de datos de clientes bancarios para identificar patrones, segmentos de clientes y señales tempranas de comportamiento relevante (por ejemplo, oportunidades de venta cruzada y perfiles de ingresos/ahorro). A partir del análisis exploratorio y las visualizaciones realizadas en la carpeta `Analisis`, se destacan los siguientes puntos:

- Objetivo: generar insights accionables para áreas de negocio (marketing, retención y riesgo) mediante limpieza de datos, análisis exploratorio y pruebas iniciales de modelado.
- Hallazgos clave (preliminares):
  - Segmentos de clientes diferenciables por edad, saldo y actividad que podrían beneficiarse de ofertas personalizadas.
  - Variables con alta correlación entre sí que requieren ingeniería de características para mejorar modelos predictivos.

# Tecnologias y Herramientas Utilizadas
* Python  
  Lenguaje base para limpieza, análisis y visualización.
  * pandas — manipulación y análisis de datos.
  * numpy — operaciones numéricas.
  * matplotlib / seaborn / plotly — visualización.
  * scikit-learn — modelado y evaluación.
  * missingno — análisis de valores faltantes.
* Entorno sugerido: JupyterLab / Jupyter Notebook o Google Colab.

# Gráficos Destacados
A continuación se listan las visualizaciones consideradas más relevantes del análisis, con el nombre de archivo sugerido para cada captura y una breve interpretación. Se recomienda guardar las imágenes en `Analisis/figures/` o `Fotos/` con los nombres indicados.

1) Distribución de edad (histograma)  
   - Archivo sugerido: Analisis/Fotos/edad_distribucion.png  
   - Interpretación: muestra la concentración de clientes por rangos de edad y permite identificar cohortes principales para campañas segmentadas.

2) Saldo por segmento (boxplot por segmento)  
   - Archivo sugerido: Analisis/Fotos/saldo_por_segmento.png  
   - Interpretación: compara la dispersión de saldo entre segmentos (p. ej. por producto o grupo etario) y ayuda a detectar outliers financieros.

3) Matriz de correlación
   - Archivo sugerido: Analisis/Fotos/matriz_correlacion.png  
   - Interpretación: muestra relaciones lineales entre variables numéricas; útil para ingeniería de características y reducción de multicolinealidad.

# Resultados y Aprendizajes
- Se realizó la limpieza inicial de los datos: tratamiento de valores faltantes, normalización de tipos y creación de variables derivadas.
- Análisis exploratorio (EDA) que incluye:
  - Distribuciones univariantes de las variables principales.
  - Matrices de correlación y análisis de relaciones entre variables.
  - Visualizaciones que ayudan a identificar segmentos y comportamientos relevantes.
- Experimentos de modelado (si los hay) y métricas iniciales: se probaron modelos básicos para clasificación/regresión (según el objetivo) y se obtuvieron métricas preliminares que permiten comparar enfoques.
- Aprendizajes clave: importancia de la ingeniería de características, valor de la visualización para identificar sesgos y outliers.

# Estado del Proyecto
 El análisis exploratorio y la documentación del proceso están en la carpeta `Analisis` (notebooks).
- Modelos iniciales y comparativas están en estado experimental.
- Predicciones segun los datos obtenidos en los diferentes analisis.
- Recomendaciones para cada caso desplegado en el analisis.

# Contacto y Enlaces
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vicente-gonzalez-escobar-9b637a1a3)</br>[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vig.gonzaleze@gmail.com) vig.gonzaleze@gmail.com