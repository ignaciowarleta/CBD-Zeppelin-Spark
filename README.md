# CBD-Zeppelin-Spark

## Tabla de Contenidos

- [Instalación](#instalación)
- [Requisitos Previos](#requisitos-previos)

## Instalación

### Requisitos Previos

Para la instalación de Apache Zeppelin y Apache Spark, se necesitará un sistema operativo compatible con Zeppelin como Linux, Windows o macOS, tener instalado Java (al menos la versión 8), al menos 4 GB de memoria RAM, espacio en disco y un navegador web. [4]

### Zeppelin

Para llevar a cabo la instalación del software Apache Zeppelin, el primer paso es dirigirse al sitio web oficial de Zeppelin, https://zeppelin.apache.org/. Una vez dentro, seleccionaremos el botón de descarga o «download». Este botón nos permitirá acceder a las opciones de descarga disponibles, donde podremos seleccionar la versión deseada por el usuario. En este caso, hemos decidido optar por la última versión disponible hasta la fecha, la 0.11.1. También hemos optado por la opción que cuenta con todos los intérpretes instalados. <img width="346" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/10eda757-204a-4ec2-a41f-671e3a619402">

Al hacer clic en la versión se nos redirigirá a la web de Apache, https://www.apache.org/dyn/closer.cgi/zeppelin/zeppelin-0.11.1/zeppelin-0.11.1-bin-all.tgz. Al hacer clic en el primer enlace que nos muestra, comenzará la descarga del programa. 
<img width="360" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/3ca8f8bc-6688-4e5d-90f1-feb7758f93cb">


Una vez descargado el archivo tgz bastaría con descomprimirlo y ejecutar los siguientes comandos en una terminal:

	cd zeppelin-(versión)-bin-all
	cd bin
	./zeppelin-daemon.sh start

Si la instalación es correcta veremos que la terminal nos devuelve un mensaje «Ok» y al dirigirnos a http://localhost:8080/#/ veríamos el siguiente mensaje de bienvenida de Zeppelin
<img width="296" alt="image" src="https://github.com/ignaciowarleta/CBD-Zeppelin-Spark/assets/100534029/28f482ca-88a6-4e6d-951b-af5786ddb740">




