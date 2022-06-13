# 22.503_PEC-4
## Programación para la ciencia de datos PEC 4
Autor: Federico Clavijo López

## Contexto
Nos han pedido que diseñemos una serie de herramientas que permitan trabajar con este tipo de datos a largo plazo, además de realizar unos análisis preliminares de los mismos. Para ello, nos han proporcionado un conjunto de datos que incluye toda la información sobre los jugadores y las jugadoras incluídas en el videojuego desde el año 2016 hasta el 2022.

## Inputs para ejecutar el programa
El programa necesita un fichero input_fclavijo0.txt, que contiene:
1. 
2. 

## Pasos para ejecutar PEC4_fclavijo0.py
1. Descargar y descomprimir fichero. El mismo fichero se encuentra en el repositorio https://github.com/fclavijo0/22.503_PEC-4/
2. cd ./PEC4_fclavijo0
3. pip install -r requirements.txt

Se decidió crear un script por cada punto solicitado con lo cual para ejecutar se debe seguir el orden: 
5. python3 .1a_gender_year_add.py
6. python3 .1b_join_dt_gender_year.py
7. python3 .1c_join_dt_years.py
8. python3 .2a_max_col.py
9. python3 .2b_dt_query.py (No funciona)
10. python3 .2c_dt_query.py
11. python3 .3a_BMI.py

Los scripts (.py) de los ejercicios 1a, 1b, 1c, 2a, 2b, 2c estan acompañados de un fichero .txt que contiene los argumentos que necesita el .py

## Outputs del programa
Cada script se buscó que mostrara el data set requerido. Es mostrado con funcion .head
Para acceder al data set completo se debe acceder a la carpeta ./data donde estan los csv riginales y los que se han obtenido. 
Los data set obtenidos son:

Ejercicio 1a:
Todos los csv originales renombrados con el año. adentro cada uno tiene las columnas gender y year, asi:
players_xx_xxxx.csv y female_players_xx_xxxx.csv

Ejercicio 1b:
dt_join_male_female_xxxx.csv

Ejercicio 1c:
dt_join_years_xxxx_xxxx.csv

Ejercicio 2a:
find_max_col_df.csv

Ejercicio 2c:
2c_dt_query_all_years.csv
2c_2_query.csv
2c_1_query.csv
