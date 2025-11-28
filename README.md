# Mi Aprendizaje en Fundamentos en Ciencia de Datos
# Universidad de Antioquia - Facultad de Ingeniería - Maestría en Ingeniería

Este repositorio incluye todo el proceso de trabajo de la materia "Introducción a la Ciencia de Datos" en el marco de estudio de la Maestría en Ingeniería.

El objetivo es crear una trazabilidad del proceso de aprendizaje de la materia "Fundamentos en Ciencia de Datos" que permita identificar, registrar y controlar
cada paso del avance en el desarrollo de las actividades.

Este repositorio está organizado con las siguientes carpetas:

- articulo/ : incluye los informes y el entregable final del proyecto de aula.
  
- proyecto_aula/ : contiene los entrgeables establecidos del proyecto de aula.
  
- sesiones_practicas/ : está estructurado con el registro de cada sesión práctica trabajada en clase.
  
- datos/ : se encuentran los datos requeridos para ejecutar los entregables del proyecto de aula

Incluye los procesos de prácticas en clase de cada tema y el Proyecto de Aula: 
"Análisis del comportamiento e identificación de patrones en el valor de las donaciones de una empresa del sector cárnico mediante técnicas de ciencia de datos"

--------------------------------------------------------------------------------------------------

**Contexto Proyecto de Aula**

La problemática de las pérdidas y desperdicios de alimentos (PDA) es crítica a nivel global y nacional, con impactos económicos, sociales y ambientales significativos. En Colombia, se desperdician grandes cantidades de alimentos mientras más de la mitad de la población enfrenta inseguridad alimentaria, generando además emisiones contaminantes y pérdidas económicas del 1,3% del PIB. Las causas son múltiples: desde ineficiencias en la producción, distribución y consumo, hasta vacíos normativos y logísticos. Aunque el país ha avanzado en legislación (Ley 1990 de 2019 y Ley 2380 de 2024), los incentivos fiscales no se corresponden con la limitada capacidad logística, que solo permite recuperar el 12% del potencial alimentario disponible. Esto evidencia la urgencia de transformar la cadena de recuperación alimentaria mediante modelos logísticos más eficientes, coordinados y adaptados al nuevo marco legal.

Puntualmente esta investigación esta enmarcada en una empresa del sector de alimentos carnicos, que tiene una excelente trazabilidad en cuanto al desperdicio de alimentos de forma global, sin embargo, las "donaciones" son un tema de interés, ya que no hay proyectos actuales que analicen este apartado, ya que es visto como una pérdida total del producto. Lo trascendental es que la existencia de alivios fiscales de gran envergadura pueden ayudar a modificar esta creencia, ya que el proceso de donación tendría un incentivo y no una pérdida del 100%. Adicionalmente contando con un plus, ya que las donaciones contribuyen directamente con propósitos sociales y ambientales.

Para el respectivo análisis, la data obtenida tiene un histórico desde el año 2022, que constituye toda la trazabilidad de alimentos destruidos (incinerados) por diferentes causas en la compañía. Esta data madre tiene un campo llamado "Tipo de desguace" que tiene tres clasificaciones: "destrucción", "reelaboración" y "donaciones". En vista de que el trabajo está enfocado en las donaciones y las destrucciones, se omite toda la información relacionada con reelaboración. Para términos legales y de información confidencial, se generó un documento de confidencialidad por parte de la empresa, en dónde no es posible utilizar su nombre propio para publicaciones o trabajos, sin embargo, para términos académicos el uso de sus datos es con total transparencia.  

-------------------------------------------------------------------------------------------------

**Objetivo Proyecto de Aula**

Analizar el comportamiento del valor de las donaciones y de la destrucción de alimentos en una empresa del sector cárnico, identificando patrones asociados a las variables que componen la data histórica desde el 2022, que permitan comprender su dinámica y servir como base para el desarrollo de modelos predictivos. Para lograr este objetivo general, se cuenta con cinco objetivos específicos:

•	Recolectar y depurar la base de datos histórica de donaciones y del desperdicio de alimentos de la empresa del sector cárnico desde el año 2022, garantizando la calidad, consistencia y completitud de la información.

•	Describir las variables relevantes asociadas al valor de las donaciones y del desperdicio de alimentos, diferenciando entre variables categóricas y numéricas, para comprender su estructura y posibles relaciones.

•	Aplicar técnicas de análisis exploratorio de datos (EDA) para identificar tendencias, patrones y comportamientos significativos en el valor de las donaciones y del desperdicio de alimentos a lo largo del tiempo.

•	Detectar y analizar valores atípicos en la base de datos para mejorar la calidad de la información, reducir sesgos y garantizar mayor confiabilidad en los resultados del procesamiento y modelado posterior.

•	Estandarizar el conjunto de datos mediante la imputación de valores faltantes, el escalamiento de variables y la aplicación de transformaciones adecuadas, asegurando un preprocesamiento que mejore la interpretabilidad y desempeño de los modelos analíticos posteriores.



--------------------------------------------------------------------------------------------------
**Justificación Metodológica**

El enfoque metodológico del proyecto se fundamenta en los principios de la ciencia de datos, orientados al análisis cuantitativo y al descubrimiento de patrones a partir de información estructurada. Se adopta un enfoque cuantitativo de tipo descriptivo y exploratorio, ya que el propósito principal es analizar el comportamiento de las variables contenidas en la base de datos e identificar relaciones o patrones significativos que expliquen el fenómeno de estudio.

Este enfoque permite aplicar herramientas estadísticas, técnicas de limpieza y transformación de datos, así como métodos de visualización y modelado, que facilitan la comprensión objetiva y basada en evidencia del comportamiento de los datos.

Además, al tratarse de un proyecto en el marco de Fundamentos de Ciencia de Datos, este enfoque resulta pertinente porque favorece el desarrollo de competencias analíticas y metodológicas en la manipulación de datos, la formulación de hipótesis, la validación empírica de resultados y la interpretación de hallazgos para la toma de decisiones o la construcción de modelos predictivos.

--------------------------------------------------------------------------------------------------
**Principales Hallazgos**

La implementación de CRISP-DM permitió revelar inconsistencias en la información, como registros de destrucciones con valores negativos y productos con código “0”, lo que resalta la importancia de fortalecer la calidad de los datos. La aplicación de Cramer’s V facilitó la reducción de la dimensión en variables categóricas, mientras que Box-Cox mejoró la distribución de las variables continuas. Pese a las limitaciones derivadas del tamaño y características de la base, se obtuvieron transformaciones valiosas y se identificaron líneas de trabajo futuras, entre ellas evaluar una variable respuesta categórica y aplicar nuevas metodologías que permitan comprender con mayor claridad el comportamiento de la data de destrucciones.

--------------------------------------------------------------------------------------------------
**¿Cómo ejecutar el código del Proyecto de Aula?**

El código para ejecutar se encuentra en la carpeta “proyecto_aula”, compuesta por cinco archivos tipo Jupyter (.ipynb), que se ejecutan en orden (01, 02, 03, 04, 05), se recomienda ejecutarlos en el local con un software como "Visual Studio Code", ya que los datos son muy pesados por su tamaño (944.083 KB)



--------------------------------------------------------------------------------------------------


Dirigido por:
Maria Bernarda SALAZAR SANCHEZ
Profesora
Coordinadora Especialización en Analítica y Ciencia de Datos
Departamento de Ingeniería de Sistemas

Autora:
Luisa Fernanda Jimenez Ramirez
Estudiante de Maestría en Ingeniería
luisa.jimenez1@udea.edu.co
