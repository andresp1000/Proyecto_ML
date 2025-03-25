# Modelos analizados en clase

A continuación, se realiza una breve descripción de cómo se puede abordar desde diferentes modelos del Machile Learning el tema de estudio: Migración Interna en Colombia.

**k-vecinos más cercanos (k-NN):**
Puede aplicarse al estudio de la migración interna en Colombia como una herramienta de clasificación o predicción basada en similitudes entre regiones, individuos o patrones migratorios (Sánchez Poveda, 2023). Este modelo permite identificar zonas del país con características socioeconómicas, demográficas o geográficas similares que puedan influir en los flujos migratorios. Por ejemplo, al considerar variables como el desempleo, el nivel educativo, el acceso a servicios públicos y la violencia, k-NN puede predecir la probabilidad de que una persona se desplace de una región a otra. Así, se pueden identificar regiones emisoras o receptoras de migrantes según su similitud con otras zonas donde ya se ha observado un comportamiento migratorio específico. Esta técnica es útil tanto para el análisis exploratorio como para la toma de decisiones en políticas públicas, al proporcionar una visión basada en datos sobre las dinámicas migratorias internas (IBM, 2017).

**Regresión Ridge:**
Es una técnica de aprendizaje supervisado que permite modelar relaciones lineales entre múltiples variables independientes y una variable dependiente, aplicando una penalización para reducir la multicolinealidad y el sobreajuste. En el contexto de la migración interna en Colombia, esta técnica puede emplearse para predecir los flujos migratorios entre departamentos o municipios a partir de variables como el ingreso promedio, la tasa de desempleo, el acceso a servicios básicos, la presencia de violencia o conflictos, y el crecimiento poblacional. La regresión Ridge permite incorporar una gran cantidad de variables explicativas sin perder precisión, lo cual es ideal cuando hay correlación entre factores sociales y económicos. Este modelo proporciona estimaciones más estables y robustas, ayudando a identificar los principales factores que impulsan los desplazamientos internos, lo cual es clave para el diseño de políticas públicas que respondan a las causas estructurales de la migración interna (Del Valle Moreno et al., 2012).

**Regresión Lasso:**
Least Absolute Shrinkage and Selection Operator, es un modelo estadístico que permite la selección de variables y la regularización en problemas de regresión, favoreciendo soluciones más simples y comprensibles. En el estudio de la migración interna en Colombia, Lasso puede ser utilizado para identificar los factores más relevantes que influyen en los desplazamientos poblacionales entre regiones, tales como el desempleo, el nivel educativo, la violencia, el acceso a salud y servicios públicos, o el desarrollo económico local. Al penalizar la magnitud de los coeficientes, este modelo tiende a reducir a cero los coeficientes de variables menos significativas, facilitando así la interpretación y priorización de políticas públicas. Su aplicación es especialmente útil cuando se trabaja con bases de datos amplias y con muchas variables correlacionadas, permitiendo construir modelos predictivos robustos y explicativos sobre los patrones migratorios internos en el país (Pacheco-Robles et al., 2023).

**Clasificador Bayesiano:**
Basado en el teorema de Bayes, es un modelo probabilístico que permite predecir la pertenencia de una observación a una clase determinada en función de evidencia previa. En el contexto de la migración interna en Colombia, este modelo puede utilizarse para clasificar a individuos o grupos poblacionales según su probabilidad de migrar de una región a otra. Usando variables como el nivel de ingresos, la edad, la educación, la violencia en la zona de origen, el acceso a servicios básicos, entre otras, el clasificador bayesiano estima la probabilidad de que una persona decida desplazarse. Este enfoque es útil para identificar perfiles migratorios y prever flujos poblacionales, lo que puede apoyar el diseño de políticas públicas más eficientes y focalizadas. Además, su simplicidad y efectividad lo hacen adecuado incluso con conjuntos de datos limitados o cuando se requiere una implementación rápida (Sucar, 2008).


**Random Forest:**
Es un algoritmo de aprendizaje supervisado que combina múltiples árboles de decisión para mejorar la precisión de las predicciones y reducir el sobreajuste. En el estudio de la migración interna en Colombia, Random Forest puede utilizarse para predecir los flujos migratorios o clasificar regiones según su probabilidad de ser emisoras o receptoras de población. Este modelo puede procesar grandes volúmenes de datos e incorporar múltiples variables como la tasa de desempleo, calidad de vida, violencia, servicios de salud, educación, y características demográficas. Una de sus principales ventajas es la capacidad de manejar datos no lineales y de identificar las variables más influyentes en los patrones migratorios. De este modo, permite generar modelos interpretables y precisos que apoyen la formulación de políticas públicas orientadas a mitigar los factores estructurales que impulsan la migración interna (Schonlau & Zou, 2020).

**XGBoost:**
Extreme Gradient Boosting, es un modelo de aprendizaje automático basado en árboles de decisión que se caracteriza por su alta precisión, velocidad y capacidad de manejo de grandes volúmenes de datos. En el contexto de la migración interna en Colombia, XGBoost puede aplicarse para predecir y clasificar patrones migratorios a partir de múltiples variables socioeconómicas, demográficas y territoriales, como la tasa de desempleo, el acceso a servicios básicos, la violencia, el nivel educativo o el crecimiento urbano. Este modelo permite identificar combinaciones complejas de factores que influyen en la decisión de migrar, además de detectar interacciones entre variables que otros modelos lineales podrían pasar por alto. Gracias a su capacidad para trabajar con datos incompletos o desequilibrados y su interpretación mediante técnicas como la importancia de variables o SHAP values, XGBoost se presenta como una herramienta robusta y efectiva para apoyar el análisis de la migración interna y orientar políticas públicas basadas en datos (Su et al., 2023).

**Máquinas de Vectores de Soporte:**
SVM, por sus siglas en inglés son modelos de aprendizaje supervisado que se utilizan para clasificación y regresión, especialmente eficaces en problemas con alta dimensionalidad y datos no lineales. En el estudio de la migración interna en Colombia, SVM puede aplicarse para clasificar individuos o zonas geográficas según su probabilidad de experimentar migración, ya sea como regiones de origen o destino. Utilizando variables como el nivel de pobreza, acceso a servicios básicos, violencia, oportunidades laborales y educación, el modelo puede encontrar una frontera óptima que separe a los grupos migrantes de los no migrantes. Además, al emplear funciones kernel, SVM puede manejar relaciones complejas entre los datos, capturando patrones no lineales en los factores que impulsan los movimientos poblacionales. Esta capacidad predictiva puede ser clave para orientar políticas públicas y anticipar dinámicas migratorias internas con mayor precisión (García Díaz & Lozano Martínez, 2006).

**Redes Neuronales:**
Las redes neuronales artificiales son modelos inspirados en el funcionamiento del cerebro humano que permiten identificar patrones complejos y no lineales en grandes volúmenes de datos. En el contexto de la migración interna en Colombia, estas redes pueden utilizarse para predecir los flujos migratorios entre regiones, basándose en múltiples variables como la tasa de desempleo, violencia, calidad de vida, educación, acceso a servicios, entre otras. Gracias a su capacidad de aprendizaje profundo, las redes neuronales pueden descubrir interacciones ocultas entre factores sociales y económicos que influyen en las decisiones migratorias. Además, se adaptan bien a datos con ruido o faltantes y permiten generar modelos altamente predictivos. Su aplicación resulta especialmente útil cuando se dispone de bases de datos complejas y extensas, como censos o registros administrativos, y puede complementar el análisis de políticas públicas enfocadas en la gestión de la movilidad interna y la reducción de desigualdades regionales(Tablada & Torres, 2021).

**Deep Learning:**
El aprendizaje profundo es una subárea del aprendizaje automático que utiliza redes neuronales con múltiples capas para modelar relaciones complejas en grandes volúmenes de datos. En el estudio de la migración interna en Colombia, este enfoque puede ser clave para analizar dinámicas migratorias con alto nivel de precisión, al procesar datos masivos como censos, registros administrativos, encuestas socioeconómicas o incluso datos satelitales. Deep Learning permite identificar patrones ocultos en variables como ingresos, empleo, violencia, acceso a educación y salud, y condiciones geográficas, ofreciendo predicciones sobre los flujos migratorios y clasificaciones de zonas de origen y destino. Su capacidad para manejar datos heterogéneos y no estructurados, como texto o imágenes, abre nuevas posibilidades para integrar fuentes diversas, como redes sociales o noticias locales, en el análisis migratorio. De esta manera, contribuye a una comprensión más profunda del fenómeno y al diseño de políticas públicas más informadas y eficaces (Janiesch et al., 2021).
 
**Referencias bibliográficas:**

Del Valle Moreno, J., Walkiria, C., & Bustillo, G. (2012). La Multicolinealidad en modelos de Regresión Lineal Múltiple. In Calero (Vol. 21, Issue 4).

García Díaz, E. E., & Lozano Martínez, F. (2006). Máquinas de vectores de soporte. Revista de Ingeniería, 24.

IBM. (2017). ¿Qué es el algoritmo de k vecinos más cercanos? | IBM. Ibm.

Janiesch, C., Zschech, P., & Heinrich, K. (2021). Machine learning and deep learning. Electronic Markets, 31(3). https://doi.org/10.1007/s12525-021-00475-2

Pacheco-Robles, R. A., Vela-Del-Águila, S., Tuesta-Hidalgo, O., Tuesta-Hidalgo, J. C., Nureña-Hidalgo, M. A., & 
Vela-Lozano, J. M. (2023). Modelo LASSO para comparar indicadores de desarrollo social y bienestar en Perú y la región suramericana. UNAAACIENCIA-PERÚ, 2(2). https://doi.org/10.56926/unaaaciencia.v2i2.29

Sánchez Poveda, S. L. (2023). La migración forzada interna en Colombia. REVISTA CONTROVERSIA, 220. https://doi.org/10.54118/controver.vi220.1286

Schonlau, M., & Zou, R. Y. (2020). The random forest algorithm for statistical learning. Stata Journal, 20(1). https://doi.org/10.1177/1536867X20909688

Su, W., Jiang, F., Shi, C., Wu, D., Liu, L., Li, S., Yuan, Y., & Shi, J. (2023). An XGBoost-Based Knowledge Tracing Model. 
International Journal of Computational Intelligence Systems, 16(1). https://doi.org/10.1007/s44196-023-00192-y

Sucar, L. E. (2008). Clasificadores Bayesianos: de Datos a Conceptos. European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases.

Tablada, C. J., & Torres, G. A. (2021). Redes Neuronales Artificiales. Revista de Educación Matemática, 24(3). https://doi.org/10.33044/revem.10280
 
