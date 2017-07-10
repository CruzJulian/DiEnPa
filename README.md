# DiEnPa

Este es el prepositorio del proyecto DiEnPa (Distancias Entre Países), que tiene como resultado una aplicación Shiny alojada en la url [DiEnPa](https://jjsligaesp.shinyapps.io/DiEnPa/).

# Resumen

El IDH (Índice de Desarrollo Humano) es un indicador usado por el PNUD (Programa de las Naciones Unidas para el Desarrollo) con el fin de determinar el nivel de desarrollo de los distintos países del mundo.  Para esto abarca tres componentes: economía, mediante PIB per cápita; calidad de vida, mediante esperanza de vida al nacer; y educación, mediante escolaridad. Asignando valores más altos a países con mayores niveles de desarrollo, 0 es el valor más bajo y 1 el valor más alto, el PNUD, mediante el IDH, clasifica los países en tres grandes grupos:

 - Países con alto desarrollo humano cuando tienen un IDH mayor de 0,80.
 - Países con medio desarrollo humano cuando tienen un IDH entre 0,50 y 0,80
 - Países con bajo desarrollo humano cuando tienen un IDH menor de 0,50.

Sin embargo, al ser un proceso social dinámico y contextual, el concepto de desarrollo humano, y el de desarrollo en sí mismo, trascienden lo reflejado en el IDH o cualquier otro índice sobre desarrollo humano. Si bien los índices son valores numéricos que cuantifican alguna característica cuya medición se dificulta y, a diferencia de un indicador, su interpretación es absolutamente contextual, en últimas, proporciona referencias cuantitativas de las carencias de los países y de las brechas existentes con respecto a posibles metas y monitorea la eficacia (o no) de las políticas nacionales.

Las políticas respecto a datos abiertos del PNUD permiten acceder a la base de datos usada para calcular el IDH. Al trabajar con estos mismos datos es posible proponer un sistema contextual de medición y monitoreo del desarrollo humano que ubica países con estados de desarrollo similares sin asignar valores cuantitativos a mayor o menor nivel de desarrollo. Esto contribuye a la deconstrucción de la idea de mejores y peores países, abre las puertas a nuevos abordajes sobre el desarrollo mismo y permite a los organismos gubernamentales de cada país obtener un panorama del desarrollo humano a nivel mundial contextualizado, que muestra países con estados de desarrollo similares al propio.

La metodología consiste tomar los datos que publica el PNUD, estandarizar los indicadores que componen el IDH, y a partir de esto crear una matriz de distancias entre países. La visualización se realiza mediante la generación automática de mapas en una aplicación web realizada en el framework Shiny de R. Como producto del estudio se obtiene un portal web interactivo donde es posible consultar, para cada país, los países con estados de desarrollo similares. Aprovechando de una manera nueva la información contenida en los indicadores y facilitando el trabajo conjunto de países con problemáticas parecidas.

