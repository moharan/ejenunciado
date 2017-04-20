# ejenunciado
Ejercicio 2 de Laboratoria

Desde Terminal
*cd* IR A 
*mkdir* nombre carpeta = para crear una carpeta en el directorio
*touch*  nombre de archivo.extensión (crea archivo sublime)
*git init* para crear un nuevo repositorio

en gitHub hacer click en *+* para crear un repositorio
en la casilla poner el nombre de la carpeta y dar creating repository
copiar este link
 *git remote add origin* https://

*git status* enumera todas las versiones del proyecto antes de commit (aparece el archivo en rojo porque no esta enlazado)
*git add .* =enlaza el archivo que no estaba reconocido (que esta en rojo)
*git status* = reconoce el archivo y queda en color verde 
*git commit -m “agrega comentarios del proyecto”* = pones un comentario de que se trata el archivo 
*git push origin master* = sube los cambios de la nueva versión, pide nombre de usuario de gitHub y luego contraseña 
actualizar el link de gibHub y ya esta el archivo

SUBIR::

*git checkout -b gh-pages*
*git status*
*git merge master*?????
*git push -u guiado gh-pages*
