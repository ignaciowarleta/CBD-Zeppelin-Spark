# CBD-Zeppelin-Spark

## Tabla de Contenidos

- [Instalación](#instalación)
- [Requisitos Previos](#requisitos-previos)
- [Zeppelin](#zeppelin)
- [Spark](#spark)

## Instalación

### Requisitos Previos

Para la instalación de Apache Zeppelin y Apache Spark, se necesitará un sistema operativo compatible con Zeppelin como Linux, Windows o macOS, tener instalado Java (al menos la versión 8), al menos 4 GB de memoria RAM, espacio en disco y un navegador web. [4]

### Zeppelin

Para llevar a cabo la instalación del software Apache Zeppelin, el primer paso es dirigirse al sitio web oficial de Zeppelin, https://zeppelin.apache.org/. Una vez dentro, seleccionaremos el botón de descarga o «download». Este botón nos permitirá acceder a las opciones de descarga disponibles, donde podremos seleccionar la versión deseada por el usuario. En este caso, hemos decidido optar por la última versión disponible hasta la fecha, la 0.11.1. También hemos optado por la opción que cuenta con todos los intérpretes instalados. 

<img width="346" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/10eda757-204a-4ec2-a41f-671e3a619402">

Al hacer clic en la versión se nos redirigirá a la web de Apache, https://www.apache.org/dyn/closer.cgi/zeppelin/zeppelin-0.11.1/zeppelin-0.11.1-bin-all.tgz. Al hacer clic en el primer enlace que nos muestra, comenzará la descarga del programa. 

<img width="360" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/3ca8f8bc-6688-4e5d-90f1-feb7758f93cb">


Una vez descargado el archivo tgz bastaría con descomprimirlo y ejecutar los siguientes comandos en una terminal:

	cd zeppelin-(versión)-bin-all
	cd bin
	./zeppelin-daemon.sh start

Si la instalación es correcta veremos que la terminal nos devuelve un mensaje «Ok» y al dirigirnos a http://localhost:8080/#/ veríamos el siguiente mensaje de bienvenida de Zeppelin

<img width="296" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/28f482ca-88a6-4e6d-951b-af5786ddb740">

### Spark

Para instalar el software Apache Spark, comenzaremos accediendo al sitio web oficial de Spark en https://spark.apache.org/. Una vez allí, encontraremos en el menú el botón de descarga o «download». Al hacer clic en este botón, se nos presentarán las opciones de descarga disponibles, donde podremos seleccionar la versión deseada y un package type. En este caso hemos optado de nuevo por la última versión disponible, la versión 3.5.1.

<img width="300" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/aed36eeb-8c09-4bc5-8637-ff42edc0bbab">

El siguiente paso es clicar el enlace que indica el apartado tres, que nos dirigirá a la web de Apache, https://www.apache.org/dyn/closer.lua/spark/spark-3.5.1/spark-3.5.1-bin-hadoop3.tgz. Una vez aquí haremos lo mismo que con el software Zeppelin, es decir, seleccionaremos el primer enlace que se muestra (ver Ilustración 7) y esperaremos a que se complete la descarga. 

<img width="345" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/c4677f24-ef03-4298-b202-ef1769a0adf0">

Una vez finalizada la descarga del archivo tgz, debemos descomprimirlo y ejecutar los siguientes comandos:

	cd spark-(versión)-bin-hadoop3
	bin/pyspark
	
Si la instalación ha sido correcta veremos que la terminal nos devuelve el mensaje que se muestra a continuación:

<img width="334" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/5aea0036-16db-421e-a3ac-0905a3d6ff1c">









