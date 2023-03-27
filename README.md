# InmersionDatos_Desafio_Aula1

Desafio de analisis de inmuebles en Bogota.

## Descripcion

Este codigo realiza el analisis estadístico de los inmuebles en Bogotá, específicamente el promedio de área de todos los inmuebles en el dataset y los 10 barrios con mayor área promedio. También se consulta otros datos estadísticos, como conteo, mediana, valores mínimo y máximo.

## Requerimientos

* Python 3.x
* pandas
* matplotlib

## Uso

1. Descargar el archivo inmuebles_bogota.csv y Barrios.csv en la misma carpeta del código.
2. Ejecutar el código.

## Funcionamiento

1. Se lee el archivo inmuebles_bogota.csv y se renombran las columnas "Baños" y "Área" a "Banos" y "Area" respectivamente.
2. Se lee el archivo Barrios.csv y se obtiene el promedio del área de cada barrio.
3. Se crea un DataFrame con los barrios y sus respectivas áreas promedio.
4. Se ordenan los barrios de mayor a menor área.
5. Se grafican los 5 primeros y 5 siguientes barrios con mayor área promedio.
6. Se muestra una tabla con los 10 barrios con mayor área promedio.
7. Se utiliza el método describe() para obtener otros datos estadísticos como conteo, mediana, valores mínimo y máximo.

## Autor

Mateo Morales - Vimofama
