En este archivo incluiremos las diferencias que hemos encontrado sobre GIT y SVN.
-----------------------------------------------------------------------------------------------------------
Pablo Jose Cerero Mateos

 Subversion (SVN) es un sistema centralizado y Git es un sistema distribuido, ese es la gran diferencia.
 
 En Git utilizar ramas es muy comÃºn y fÃ¡cil, mientras que en SVN es algo mas complicado y no habitual.
 
------------------------------------------------------------------------------------------------------------


Enrique Rapela Castejón

En SVN solamente nos permite tener un único repositorio, en Git tenemos repositorios distribuidos, por lo cual es más dificil en Git saber donde están los archivos ubicados.

En los comandos git en sencillez está muy por delante, dado que para crear un repositorio en SVN tendriamos que poner estas lineas de comandos:

svnadmin create /ruta/del/repositorio
svn import /ruta/del/repositorio "http://ejemplo.com/svn" -m "Iniciando repositorio"

Y en Git es mucho más fácil e intuitivo:
Primero nos vamos al directorio donde vamos a crear el repositorio.

git init

O para añadir un repositorio que tenemos en Git Hub:
Nos vamos al directorio:

git clone http:/github.com/repositorioPruebas


--------------------------------------------------------------------------------------------------------------------------------
