## Proyecto Integrador Hospitales

## Objetivo:

Definir el mejor modelo de clasificacion para conocer si una persona que ya ha pasado por un procedimiento de biopsia y ha presentado una serie de sintomas debe ser hospitalizada o no. Esto se realiza usando los conocimientos adquiridos en los 6 modulos y haciendo prueba y error para encontrar el mejor modelo que se adapte a los datos de la base de datos.

* Hacer ETL de los datos para pasarlos a una base de datos limpia.
* Usar dos modelos de Machine Learning para clasificar una posible hospitalizacion o no.

## Archivos:
- BBDD_Hospitalización_sin balancear.csv: Estos datos provienen del dataset original, los datos no estan balanceados.
- BBDD_Hospitalización_sobremuestreo.csv: Estos datos tienen sobremuestreo para equilibarlos.
- Proyecto_Integrador_2A_Preparacion_de_datos.ipynb: Desarrollo de la limpieza de los datos y exploración.
- Proyecto_Integrador_3_Modelamiento.ipynb: Desarrollo de los modelos de ML sin el sobremuestreo.
- Proyecto_Integrador_3_Modelamiento_sobremuestreo.ipynb: Desarrollo de los modelos de ML sin el sobremuestreo.


## Resultados:

* En base a lo aprendido durante los 6 modulos, en el repositorio se pudo comprobar la mejor forma de desarrollar en el proyecto, es por ello que se uso dos bases de datos, pues en una de ellas se intentó realizar el sobremuestreo para equilibrar los datos.
* El modelo que mejor se adapta a los datos es el de arbol de desicion, pues como se puede ver en el archivo de Proyecto_Integrador_3_Modelamiento.ipynb las metricas resultan ser las mejores.
* Los mejores resultados que se encontraron fueron usando la base de datos sinn sobremuestreo, usando esa base de datos se tuvo que equilibrar los datos con los hiperparametros ** stratify y ** weight.
