# HadoopHDFS_HiveProject
# Proyecto de Carga de Datos de Vuelos en HDFS y Consulta con Hive

## Descripción

Este proyecto demuestra cómo cargar una tabla de vuelos de la compañía AIRFLOW para el año 2020 en HDFS
y cómo consultarla utilizando Hive.

La tabla contiene información sobre los vuelos, incluyendo el ID del vuelo, la aerolínea, el origen, el destino, la fecha y el retraso. 

Subire el archivo flights.csv a HDFS. 
La tabla está en formato CSV y su tamaño es de 1025 MB. 
Cargaremos esta tabla en HDFS con una replicación predeterminada de 3, lo que resultará en 27 DataNode.
Este proceso se realiza utilizando **Cloudera.**

[AQUÍ PUEDES VER EL CÓDIGO EN BASH DE LINUX.](https://github.com/elena210910/HadoopHDFS_HiveProject/blob/main/Shell_script) 

AQUI PUEDES VER EL RESULTADO FINAL!
![IMAGINL](https://github.com/elena210910/HadoopHDFS_HiveProject/blob/main/cloudera.PNG)

