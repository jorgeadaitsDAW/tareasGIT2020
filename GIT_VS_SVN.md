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

Antonio Vladimir Ortega Chinchilla:
Respecto al control de versiones: SVN es un sistema centralizado, mientras que GIT es un sistema distribuido.
Respecto al historial de modificaciones realizadas: en SVN, solo se realizan en el almacén central; las copias 
de trabajo que tienen los usuarios solo incluyen la versión más reciente. En cuanto a Git, el historial de 
cambios se puede ver tanto en el almacén como en las copias individuales.


Rafael Oliva Ramirez: 
- Primera Diferencia:
			*SVN: Es un sistema centralizado.
			*GIT: Es un sistema distribuido.
- Segunda Diferencia:
			*SVN: Se realizan en el almacén central, las copias de trabajo que tienen los usuarios solo incluyen la versión más reciente.
			*GIT: El historial de cambios se puede ver tanto en el almacén como en las copias individuales.
