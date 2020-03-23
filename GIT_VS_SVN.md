En este archivo incluiremos las diferencias que hemos encontrado sobre GIT y SVN.

Pablo Jose Cerero Mateos:

Subversion (SVN) es un sistema centralizado y Git es un sistema distribuido, ese es la gran diferencia.

En Git utilizar ramas es muy comÃºn y fÃ¡cil, mientras que en SVN es algo mas complicado y no habitual.

Enrique Rapela Castejón:

En SVN solamente nos permite tener un único repositorio, en Git tenemos repositorios distribuidos, por lo cual es más dificil en Git saber donde están los archivos ubicados.

En los comandos git en sencillez está muy por delante, dado que para crear un repositorio en SVN tendriamos que poner estas lineas de comandos:

svnadmin create /ruta/del/repositorio svn import /ruta/del/repositorio "http://ejemplo.com/svn" -m "Iniciando repositorio"

Y en Git es mucho más fácil e intuitivo: Primero nos vamos al directorio donde vamos a crear el repositorio.

git init

O para añadir un repositorio que tenemos en Git Hub: Nos vamos al directorio:

git clone http:/github.com/repositorioPruebas

Jose Antonio Reina Montes: 
En SVN los cambios realizados no se pueden fusionar entre sÃ­, ademÃ¡s se pueden registrar directorios vacÃ­os, renombrados y mudados de sitio sin pÃ©rdidas de su historia. En Git los cambios se transfieren rÃ¡pidamente al repositorio central,ademÃ¡s registra los contenidos de los directorios, por eso los vacÃ­os se eliminan automÃ¡ticamente.

Adrian Haba: 
1- En SVN los ficheros se encuentran alojados en un repositorio central, y en GIT cada uno es su propio servidor. 2- En GIT un commit no es más que una secuencia de cambios aplicados sobre una versión anterior, una fecha, un autor y un identificador, y en SVN son ficheros completos que luego se comparan para ver diferencias


Jose Manuel: 

SNV y Git son controles de versiones, snv es centralizado y git es 
distribuido y ahra veremos cuando es mejor utilizar uno u otro.

SNV: 
1. Tenemos equipos de trabajo pequeños.
2. Conocemos a todos los involucrados en el desarrollo del proyecto.
3. Cuando no necesitamos un repositorio complejo.
4. No se tiene una infraestructura para mantener varios repositorios

Git:
1. Cuando tenemos equipos muy medianos a grandes.
2. No conocemos a todos los involucrados en el desarrollo del proyecto.
3. Cuando mantener es necesario mantener una jerarquía de confianza en las personas que afectan el repositorio.
4. Cuando nuestro proyecto está enfocado a la comunidad y que estamos dispuesto a compartir nuestro código.
