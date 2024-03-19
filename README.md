## Minería de datos 2024: Censo Nacional de Población y Vivienda de 2018

Este es el repositorio de un proyecto de minería de datos con los datos del censo nacional de Colombia</br >
que tomó lugar en el año 2018. En este proyecto nos enfocaremos en estudiar los datos correspondientes a las ciudades</br >
de Medellín y Bogotá. 
</br >
El objetivo de este estudio es:
</br >
- Realizar un análisis exploratorio de los datos.
- Realizar el procesamiento de datos necesario para crear indicadores de pobreza basado en varias variables, utilizando métodos de reducción de dimensionalidad para crear estas componentes mencionadas.
- Encontrar patrones en la distribución espacial de los indicadores de pobreza en ambas ciudades utilizando modelos de Machine Learning y comparar cómo se presenta este fenómeno en las dos urbes.
</br >
El modelo de datos propuesto para este proyecto lo podemos encontrar en el directorio ./Diagrams/censo_data_model.png.
</br >
Este dataset se ajusta a ambos esquemas de almacenamiento, data warehouse y data lake, pues podríamos realizar un pipeline ETL y disponer los datos ya estructurados y "limpios" para ser consultados y consumidos por los servicios externos. También podríamos implementar un esquema data lake, en el cual extraemos y guardamos los datos en bruto en un repositorio (puede ser local o en la nube, por ejemplo, en S3) y luego seleccionar los datos necesarios y realizar una transformación específica para un problema específico (ELT), siguiendo una arquitectura de medalla (bronze, silver, gold). 
</br >
Las fuentes de datos son las siguientes:
</br >
*  Metadatos | Diccionario de datos: ./docs/metadata.xlsx.
*  Links para descargar los datasets: ./docs/data_source.txt.
