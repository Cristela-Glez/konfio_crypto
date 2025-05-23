# konfio_crypto
Coding Challenge - Bitcoin Price

Buen dia, para ejecutar los codigo de python de forma local, utilice Visual Code. Para la extracción de la información de Bitcoin me conectaba ala BD de Amazon Redshift utilizando Pandas y se extraia la información y en un dataframe se realizaba el calculo promedio movil de 5 dias posterior lo almacene en un .csv
Y lo ejecutaba de la siguiente forma desde la terminal. 
python test_bitcoin.py
Para la carga de datos con pyspark aqui fue mas complicado por el ambiente local, ya que tuve que instalar diversas librerias(pypsark,java home, hadoop_home) por lo que no tuve exito ejecutando desde visual Code, lo cual lo resolvi desde Power Shell, dando de alta los servicios necesarios y ejecutando de la siguiente forma python bitcoin_pyspark.py.
