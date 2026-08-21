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

## Evidencia de control de versiones

## Reflexión sobre feedback radicalmente sincero

## Checklist de entrega
