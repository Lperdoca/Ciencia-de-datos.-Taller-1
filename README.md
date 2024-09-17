# Ciencia de datos. Taller 1

El objetivo de este taller es realizar análisis de datos utilizando técnicas estadísticas y de visualización que permitan entender un conjunto de datos, descubrir insights y sugerir accionables al negocio.

###### Contexto del negocio

Inversiones inmobiliarias para alquiler vacacional. El objetivo es, a través del análisis de datos, ayudar a individuos o empresas que buscan invertir en propiedades para alquiler a través de la plataforma AirBnb en la ciudad de Santiago de Chile, teniendo en cuenta atributos como ubicación, detalles del host, tipo de propiedad, precio, disponibilidad futura, calificaciones, entre otros.

Mediante el uso de técnicas estadísticas y de visualización de datos se espera descubrir patrones, tendencias y oportunidades que puedan ser de interés para un inversionista.


**Tabla de Contenido**
* [Estratégia de Análisis](#estrategia-de-analisis)
* [Conclusiones](#conclusiones)
* [Instrucciones de Ejecución](#instrucciones-de-ejecucion)
* [Autores](#autores)


#### Estratégia de Análisis
###### Punto 3 taller

Para establecer la mejor opción de inversión inmobiliaria basada en los datos de Airbnb en Santiago de Chile, la estrategia de análisis se desarrolló en varias etapas que permitieron identificar patrones y tendencias clave.

En primera instancia, se realiza un análisis básico para garantizar la calidad y limpieza de los datos antes de realizar cualquier análisis estadístico o de visualización; en esta fase inicial se identificaron valores nulos, inconsistencias y posibles outliers. Una vez el dataset se encuentra limpio se realiza un análisis descriptivo para el entendimiento de los datos, con enfoque en las variables precio, ubicación, tipo de propiedad, calificaciones de los usuarios y comodidades de los inmuebles. El análisis estadístico aplicado a las variables mencionadas incluye cálculos como la media, mediana, desviación estándar, percentiles, entre otros. 

Posteriormente, se lleva a cabo un análisis univariado y multivariado utilizando visualizaciones como histogramas, gráficos de barras, mapas de calor, diagramas de cajas y de violín, así como gráficos de dispersión y de densidad, logrando identificar relaciones entre las variables clave mencionadas y patrones importantes en los datos. También se aplicaron técnicas más avanzadas, como regresiones y análisis de clustering, para agrupar propiedades con características similares, determinar los sectores más prometedores para la inversión e identificar las zonas con mejor rentabilidad potencial, brindando a los inversionistas una base sólida para tomar decisiones informadas.

Finalmente, se aplican los test de Mann-Whitney y Chi-squared e integran todos estos resultados para proporcionar recomendaciones claras y basadas en datos.

#### Conclusiones

Con base en el análisis realizado, se recomienda enfocar las inversiones en comunas que presentan un balance adecuado entre precio y demanda, como Providencia y Las Condes, con una preferencia por departamentos o casa enteras que ofrezcan una capacidad de alojamiento para 4 personas y combinación de comodidades clave como WiFi, agua caliente y cocina equipada, dado su impacto en la satisfacción del usuario y la tasa de ocupación.

Estas propiedades, ubicadas en áreas de alta demanda y bien calificadas por los usuarios, presentan una mayor rentabilidad a largo plazo. 

Estas recomendaciones están basadas en un análisis detallado de datos y estadísticas, proporcionando una base sólida para maximizar las probabilidades de éxito en el competitivo mercado de alquiler vacacional de Santiago de Chile.


#### Instrucciones de Ejecución

Se generaron dos notebooks para el desarrollo de los puntos 2 y 4 del taller los cuales deben ejecutarse en el siguiente orden: 
1. EDA_AirBnb_Santiago de Chile
2. Hypothesis-testing_AirBnb


#### Autores

| Organización   | Nombre | Correo electronico | 
|----------|-------------|-------------|
| Uniandes |  Lizeth Viviana Perdomo Castañeda | lv.perdomoc1@uniandes.edu.co |
