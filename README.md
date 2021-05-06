# Bienvenidxs al Meetup Reportando resultados estadísticos con 'report'
## Fecha: 06 de mayo 2021
## Slides: https://rladiescuerna.github.io/meetup_2021_mayo/slides/slides-report.html#1

## Detalles:

En esta sesión aprenderemos a automatizar los resultados de un análisis estadístico en R para crear reportes estandarizados y que a su vez sean fáciles de entender. Para esto, utilizaremos el paquete **report**. Este es un paquete perteneciente al easyverse que fue creado para enlazar los resultados de los análisis obtenidos en R con un manuscrito. 

## Pontente:
Nuestro invitado es [Carlos A. Torres Cubilla](https://carlostorrescubila.github.io), científico de datos en el área bancaria con experiencia en lenguajes de programación como R y Python y con conocimientos en estadística, big data y machine learning . 

## CONOCIMIENTOS PREVIOS REQUERIDOS: 
Este meetup está dirigido a personas con conocimientos básicos de R y estadística. 

## TEMARIO:
- ¿Qué es report? ¿Para qué sirve?
- Reportes no estadísticos
- Reportes estadísticos
- Aplicación real de report en un informe

## REQUERIMIENTOS DE SOFTWARE:
- `R >= 3.5` y R Studio preferiblemente en versión 1.4 (más actual)
- Paquetes de R: `report`, `palmerpenguins`, `dplyr`, `rmarkdown`, `ggpubr`

Puedes usar los siguientes comandos para su instalación:
```
packages <- c("report", "palmerpenguins", "dplyr", "ggplot2", "rmarkdown") # Paquetes
installed_packages <- packages %in% rownames(installed.packages())         # Check de los paquetes
if (any(installed_packages == FALSE)) {
  install.packages(packages[!installed_packages], dependencies = TRUE)     # Instalación
}
```

## MATERIALES

Puedes descargar estos materiales dando click en el botón Code > Downloawd zip.

De forma alternativa puedes ejecutar el siguiente comando desde tu sesión de R:

```
usethis::use_course("RLadiesCuerna/meetup_2021_mayo")
```
