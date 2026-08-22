# De una base de Excel a un dashboard en Power BI

## Contexto
El proyecto consistió en desarrollar un dashboard de análisis de ventas utilizando **Power BI**, a partir de una base de datos almacenada en **Excel**.

La información disponible estaba organizada en diferentes tablas relacionadas con ventas, productos, clientes, vendedores, territorio y métodos de pago. A partir de estos datos, el objetivo era transformar la información disponible en indicadores y visualizaciones que facilitaran el análisis y la toma de decisiones.

Entre los principales indicadores desarrollados se encontraban las **ventas totales, costos totales, rentabilidad y cantidad de unidades vendidas**. Además, el dashboard debía permitir analizar la evolución de los resultados a lo largo del tiempo y observar el comportamiento de las ventas desde diferentes perspectivas.

El desarrollo del proyecto implicó no solamente construir las visualizaciones finales, sino también preparar los datos, establecer correctamente el modelo de información y desarrollar los cálculos necesarios mediante **DAX** para obtener resultados confiables.

## Problema
Durante el desarrollo del dashboard surgieron diferentes desafíos relacionados principalmente con la **preparación de los datos, el modelado y la construcción de los cálculos necesarios para el análisis**.

Uno de los primeros desafíos fue comprender la importancia de revisar y preparar correctamente la base de datos antes de comenzar con las visualizaciones. La presencia de filas vacías y la necesidad de verificar la estructura de las diferentes tablas hicieron necesario realizar una etapa previa de validación de los datos.

Otro desafío importante fue la creación y utilización de una **tabla calendario**. Para analizar correctamente la evolución de las ventas por mes y año era necesario contar con una estructura temporal adecuada y relacionarla correctamente con los datos de ventas.

También surgieron dificultades durante la creación de **medidas DAX**. El desafío no consistía únicamente en obtener una fórmula que funcionara, sino en comprender qué calculaba cada medida, qué información utilizaba y cómo afectaba al resultado mostrado en las visualizaciones.

Finalmente, el proyecto requería transformar diferentes requisitos de análisis en indicadores y gráficos concretos. Esto implicó revisar varias veces los resultados y realizar ajustes hasta conseguir que las visualizaciones representaran correctamente la información solicitada.

El principal problema identificado fue haber comenzado a pensar en algunos indicadores y visualizaciones mientras todavía se estaba consolidando la preparación de los datos, el modelo y la lógica de los cálculos. Esto produjo dudas y retrabajo durante el desarrollo.


## Acciones
Para resolver los desafíos encontrados se trabajó de manera progresiva, revisando cada etapa del proyecto antes de avanzar hacia la construcción final del dashboard.

**1. Revisión y preparación de los datos.**
Se revisó la información proveniente de Excel, identificando filas vacías y verificando la estructura de las tablas utilizadas. Esta etapa permitió trabajar posteriormente sobre una base más consistente.

**2. Revisión del modelo de datos.**
Se analizaron las diferentes tablas y sus relaciones para asegurar que la información pudiera utilizarse correctamente dentro del modelo de Power BI.

**3. Creación de la tabla calendario.**
Se incorporó una tabla calendario para disponer de una estructura temporal que permitiera analizar las ventas por períodos, especialmente por mes y año.

**4. Construcción y comprensión de las medidas DAX.**
Se desarrollaron las medidas necesarias para obtener indicadores como ventas, costos, rentabilidad y unidades vendidas. Durante esta etapa se priorizó comprender la lógica de cada cálculo en lugar de limitarse a reproducir fórmulas.

**5. Construcción de las visualizaciones.**
Una vez preparados los datos y los cálculos principales, se desarrollaron las visualizaciones necesarias para representar los indicadores y facilitar su interpretación.

**6. Validación y ajustes.**
Finalmente, se revisaron los resultados obtenidos y se realizaron ajustes en cálculos y visualizaciones para comprobar que la información presentada respondiera correctamente a los requisitos del proyecto.

Este proceso permitió pasar de un enfoque inicial más orientado a construir rápidamente el dashboard a una metodología de trabajo más ordenada, donde cada etapa se valida antes de avanzar hacia la siguiente.


### Post-mortem constructivo
El análisis posterior del proyecto permitió identificar que las dificultades encontradas no estuvieron relacionadas con un único error, sino con el **orden en el que se abordaron algunas etapas del desarrollo**.

### Descripción del problema

Durante las primeras etapas se comenzó a pensar en indicadores y visualizaciones mientras todavía se estaba consolidando la preparación de los datos, el modelo y algunos cálculos en DAX. Como consecuencia, fue necesario volver sobre etapas anteriores para realizar verificaciones y ajustes.

### Causa raíz

La principal causa identificada fue no haber definido desde el comienzo una secuencia suficientemente clara para desarrollar el proyecto. Antes de construir las visualizaciones era necesario completar y validar primero la preparación de los datos, el modelo de datos y las medidas que alimentarían los indicadores.

### Impacto

El principal impacto fue el **retrabajo**. Algunas decisiones tuvieron que revisarse a medida que se comprendía mejor la estructura de los datos y el funcionamiento de los cálculos. Si bien esto no impidió completar el proyecto, hizo que algunas etapas demandaran más tiempo del necesario.

### Acciones correctivas

Para resolver estas dificultades se revisaron los datos y sus relaciones, se incorporó una tabla calendario, se desarrollaron y verificaron las medidas DAX y posteriormente se ajustaron las visualizaciones de acuerdo con los resultados obtenidos.

También se adoptó un enfoque orientado a comprender la lógica de los cálculos antes de utilizarlos, evitando depender únicamente de fórmulas sin comprender su funcionamiento.

### Acciones preventivas

Para futuros proyectos se estableció una secuencia de trabajo más ordenada:

**Preparación de datos → Modelo de datos → Cálculos y medidas → Validación → Visualizaciones.**

Además, se considera importante validar los resultados en cada etapa antes de avanzar a la siguiente y documentar los cambios relevantes durante el desarrollo.

### Lección principal

El principal aprendizaje fue comprender que un dashboard no comienza con los gráficos. La calidad de las visualizaciones depende de que los datos, el modelo y los cálculos que las sustentan sean correctos.

El problema permitió transformar una forma de trabajo inicialmente orientada a obtener rápidamente un resultado visual en un proceso más estructurado, comprensible y reproducible.


## Aprendizajes
El desarrollo del proyecto permitió obtener aprendizajes que pueden aplicarse a futuros trabajos de análisis de datos.

**1. Preparar los datos antes de visualizar.**
Antes de construir gráficos o indicadores es necesario revisar la calidad y estructura de los datos que serán utilizados.

**2. Construir un modelo sólido.**
Las relaciones entre las tablas y una estructura temporal adecuada, como la tabla calendario, son fundamentales para obtener análisis consistentes.

**3. Comprender DAX en lugar de memorizar fórmulas.**
Uno de los aprendizajes más importantes fue entender qué calcula cada medida, qué datos utiliza y cómo responde al contexto del análisis. Esto permite detectar errores y adaptar los cálculos a nuevos requerimientos.

**4. Validar antes de avanzar.**
Comprobar los resultados después de cada etapa permite detectar problemas de manera temprana y reducir el retrabajo.

**5. Pensar primero en la necesidad de información.**
Una visualización no debe incorporarse solamente porque resulte atractiva. Cada indicador o gráfico debe responder a una pregunta o necesidad concreta de análisis.

En conjunto, estos aprendizajes permitieron comprender que desarrollar un dashboard implica mucho más que crear visualizaciones: requiere preparar los datos, modelarlos correctamente, construir cálculos confiables y comunicar los resultados de manera clara.

## Evidencia de control de versiones
El desarrollo y la documentación de este proyecto fueron gestionados mediante GitHub, utilizando control de versiones para registrar de manera progresiva los cambios realizados.

La entrada del blog fue construida mediante diferentes commits, separando la incorporación del contexto, los problemas identificados, las acciones realizadas, el análisis post-mortem y los aprendizajes. Esto permitió mantener un historial claro de la evolución de la documentación.

Además, para incorporar la reflexión sobre el feedback recibido se creó una rama independiente denominada feature-feedback-reflection. El cambio fue registrado mediante un commit y posteriormente integrado a la rama principal mediante un Pull Request.

Este flujo permitió aplicar una práctica habitual de control de versiones:

Rama → Cambio → Commit → Pull Request → Revisión → Merge

De esta manera, cada modificación relevante quedó registrada y puede ser consultada posteriormente, facilitando la trazabilidad del proyecto.

### Enlaces de evidencia

- [Pull Request #1 - Reflexión sobre feedback]
https://github.com/antorieta-ux/blog-tecnico-powerbi/pull/1

## Reflexión sobre feedback radicalmente sincero

Durante la evaluación del proyecto recibí un feedback que destacó como fortalezas la limpieza y el modelado de los datos, la documentación del proceso de ETL mediante Power Query, el cumplimiento de las visualizaciones solicitadas y la implementación de funcionalidades como tooltips personalizados.

Al mismo tiempo, se señalaron oportunidades concretas de mejora. Entre ellas, incorporar en la documentación una captura de la configuración utilizada para el formato condicional, continuar profundizando en DAX mediante cálculos de inteligencia de tiempo y practicar la creación de botones de navegación entre páginas para mejorar la experiencia del usuario.

Este feedback me permitió comprender que un proyecto no debe evaluarse solamente por el resultado visual final. **También es importante documentar y evidenciar el proceso técnico utilizado para llegar a ese resultado.** Por ejemplo, aunque el formato condicional estuviera correctamente implementado, documentar su configuración habría permitido demostrar con mayor claridad cómo fue construido.

La devolución también me permitió identificar próximos objetivos de aprendizaje, especialmente profundizar en DAX y mejorar la navegación y experiencia de usuario de futuros dashboards.

Considero que este feedback fue útil porque combinó el reconocimiento de los aspectos logrados con observaciones específicas y aplicables. En lugar de interpretar los puntos de mejora como una crítica al trabajo realizado, los tomé como información concreta para continuar mejorando mi forma de desarrollar y documentar futuros proyectos.


## Checklist de entrega
