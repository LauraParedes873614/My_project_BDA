# My_project_BDA
Introducción al problema:

El Banco de Alimentos maneja una amplia variedad de empleados y voluntarios, quienes rotan constantemente y no necesariamente poseen conocimientos sobre el manejo y la gestión de datos. Por esta razón, se ha propuesto la creación de una página web para facilitar la gestión, consulta y visualización de los datos. Esto podría beneficiar al Banco de Alimentos en la toma de decisiones informadas, como la asignación de recursos a sectores específicos, la planificación de rutas de transporte y la selección de productos a adquirir. Los datos fueron proporcionados directamente por el Banco de Alimentos y constituyen una base de datos altamente confiable que refleja la frecuencia, sectores, organizaciones, etc., de las donaciones.

Los datos son principalmente categóricos, con la excepción de la frecuencia de donación en días, que es numérica. Para su análisis, se clasificaron numéricamente. Los datos también fueron sometidos a un proceso de limpieza para abordar datos incompletos, errores de redacción y falta de homogeneidad en la escritura de categorías.

Almacenamiento de datos:

La base de datos principal se encuentra en una hoja de cálculo de Google, ya que es donde el Banco almacena sus datos habitualmente, lo que facilita su uso colaborativo por parte de varios empleados y voluntarios. Además, en mi análisis realizado en Google Colab, se crearon bases de datos en SQL utilizando la librería SQLite. Los datos se estructuraron en las bases de datos según el orden numérico asignado a cada categoría.

Tratamiento de datos:

Las herramientas iniciales para el análisis incluyeron la función de búsqueda y reemplazo de Excel (Ctrl + H) para convertir las categorías en valores numéricos. En el análisis realizado en Python, se utilizaron técnicas como la moda, la varianza, tablas de frecuencia y diferentes tipos de gráficos, como el de torta y el de violín. No fue necesario emplear técnicas de procesamiento de lenguaje natural (NLP) ni análisis de imágenes.

Análisis descriptivo de los datos:

Las características estadísticas clave de los datos incluyeron principalmente la moda para las variables categóricas y la desviación estándar y la media para la variable numérica. Se identificaron numerosos patrones en los datos, aunque no se encontró correlación entre ellos. Por ejemplo, el grupo poblacional más representativo fue "Tejiendo Comunidad" con un 24.8%, la localidad más representativa fue Sumapaz con el 12.7%, la red territorial más relevante fue Santa Isabel de Hungría con el 10.9%, el día más frecuente de donaciones fue el miércoles con un 20.3%, y la mayoría de las donaciones se hacen quincenalmente, representando un 56.4% del total. En el notebook de Colab se incluyeron códigos, gráficos y explicaciones detalladas para facilitar la comprensión y replicabilidad del análisis.
