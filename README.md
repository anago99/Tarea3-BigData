# Tarea3-BigData
Código desarrollado para en análisis en batch (Spark).
# Análisis de datos COVID-19 con Spark

## Problema
Analizar los casos positivos de COVID-19 en Colombia para identificar patrones como distribución por sexo, departamento y edad.

## Dataset
Datos abiertos de Colombia (50,000 registros)
https://www.datos.gov.co/resource/gt2j-8ykr.csv?$limit=50000

## Tecnologías
- Apache Spark
- Python
- Hadoop HDFS

## Descripción de la solución
Se desarrolló un proceso de análisis de datos utilizando Apache Spark, donde:
1. Se cargan los datos desde el dataset.
2. Se realiza limpieza y transformación de la información.
3. Se ejecutan consultas para obtener métricas clave.
4. Se generan resultados agregados para su análisis.
   
## Ejecución
python3 batch_covid.py

## Resultados
- Casos por sexo
- Casos por departamento
- Promedio de edad
- Tipo de contagio
