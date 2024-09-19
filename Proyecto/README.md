# Desigualdad Salarial de Género en Chile 2022: Análisis en Iguales Condiciones Laborales

## Descripción del Proyecto

Este proyecto de investigación tiene como objetivo analizar la desigualdad salarial de género en Chile para el año 2022, enfocándose en comparaciones bajo las mismas características laborales. Se utilizaron datos de la Encuesta de Caracterización Socioeconómica Nacional (CASEN) y la Encuesta Nacional de Empleo (ENE) buscando verificar esta brecha en mismas circunstancias de trabajo y además evaluar los posibles factores que promuevan una brecha salarial en diferentes áreas y posiciones laborales.

La hipótesis central de esta investigación es que, en promedio, las mujeres en Chile reciben salarios inferiores a los de los hombres cuando se encuentran en igualdad de condiciones laborales.

Esta investigación se encuentra basada en un análisis previo donde se identificó una brecha salarial de género. Ahora, el objetivo es profundizar en esta brecha para comprender mejor sus causas y características. El proyecto anterior está disponible en el siguiente [repositorio de GitHub](https://github.com/ElK1000o/Taller-Ciencia-de-Datos-I/tree/main/Proyecto "Análisis de los Ingresos Principales en Chile: Una Perspectiva Demográfica, Regional y Comparativa con el Sueldo Mínimo").

## Objetivos

1. **Comparación de distribuciones laborales**: Comparar si, en general, hombres y mujeres tienen distribuciones similares en términos de condiciones laborales (área y puesto).

2. **Análisis de factores adicionales**: Examinar otros factores que podrían influir en la brecha salarial, tales como la industria, el tipo de ocupación, el nivel educativo, y el rol dentro del hogar.

3. **Análisis de encuestas CASEN y ENE**: Utilizar las encuestas CASEN y ENE del año 2022 para obtener datos demográficos y económicos, y realizar análisis comparativos entre ambos géneros.


## Metodología

1. **Recolección de Datos**:

   - **Encuesta de Caracterización Socioeconómica Nacional (CASEN) 2022**:

     - Datos obtenidos desde el sitio web del [Observatorio Social - Ministerio de Desarrollo Social y Familia](https://observatorio.ministeriodesarrollosocial.gob.cl/encuesta-casen-2022 'Observatorio Social | Desarrollo Social y Familia').

     - [Enlace de descarga directa](https://observatorio.ministeriodesarrollosocial.gob.cl/storage/docs/casen/2022/Base%20de%20datos%20Casen%202022%20SPSS_18%20marzo%202024.sav.zip "ZIP CASEN 2022"), que contiene el libro de código y datos.

   - **Encuesta Nacional de Empleo (ENE) 2022**:

     - Información disponible en el [Instituto Nacional de Estadística](https://www.ine.gob.cl/estadisticas/sociales/mercado-laboral/ocupacion-y-desocupacion "INE").

     - Para los datos: Bases de datos > Bases anualizadas > Formato CSV > Año 2022.

     - [Enlace directo de los datos](https://www.ine.gob.cl/docs/default-source/ocupacion-y-desocupacion/bbdd/bases-anuales/csv/ano-2022.csv?sfvrsn=c55b558c_16&download=true "Datos ENE 2022").

     - Para el libro de código: Bases de datos > Libro de Códigos > Libro de Códigos Base ENE 2020 - 2024.

     - [Enlace directo de libro de código](https://www.ine.gob.cl/docs/default-source/ocupacion-y-desocupacion/bbdd/libro-de-codigos/codigos-ene-2020.pdf?sfvrsn=54753851_64 "Libro de códigos ENE 2022").

2. **Procesamiento de Datos**: 

    - Los datos de la encuesta CASEN y ENE se procesaron en Python para su posterior análisis y visualización.


## Herramientas

El análisis será realizado utilizando **Python** y las siguientes librerías:

- `pandas`: Para la manipulación y análisis de datos.

- `numpy`: Para cálculos numéricos.

- `matplotlib` y `seaborn`: Para la visualización de datos.

## Organización del repositorio

El repositorio se encuentra organizado en las siguientes carpetas y archivos:

- **Casen/**: Correspondiente a cuestionario en pdf de la encuesta y libro de código (excel).

- **ENE/**: Correspondiente libro de código de la encuesta en pdf.

- **Informe/**: Esta carpeta contiene el informe en $LaTeX$ (.tex) y en pdf. 

- **input/**: Contiene datos de origen (carpeta `data`) y visualizaciones del [proyecto anterior](https://github.com/ElK1000o/Taller-Ciencia-de-Datos-I/tree/main/Proyecto "Análisis de los Ingresos Principales en Chile: Una Perspectiva Demográfica, Regional y Comparativa con el Sueldo Mínimo") (carpeta `fig`). 

- **output/**: Contiene datos procesados (carpeta `data`) y gráficas correspondientes a dichos datos (carpeta `fig`).

- **Python/**: Corresponde a procesamiento (carpeta `Procesamiento`) y análisis (carpeta `Analisis`) utilizando Jupyter Notebook de Python.

## Notas

- Los datos de la encuesta CASEN fueron convertidos a formato .csv ya que se encontraban en extensión .sav (SPSS) al momento de la descarga.

- La última visita a cada enlace entregado fue el 04 de septiembre de 2024.

## Respecto al proyecto

**Profesor a cargo**: Ariel Norambuena  
**Estudiante**: Camilo Riquelme Horta
