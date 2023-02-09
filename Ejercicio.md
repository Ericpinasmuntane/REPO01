

# EJERCICIO 1:
**1.1 – Crea un directorio llamado repo01 en local (desde tu máquina) e
ejecuta el comando pertinente  
para que dicho directorio para que se transforme el repositorio en local ¿Cómo
podemos identificar que el repositorio se ha inicializado?**

_Imagen1_

_Podemos saber si el repositorio se h iniciado utilizano el comando git status y comprobar en la carpeta que hay el fichero .git_

_Imagen2_

**1.2 – Añade un documento llamado readme.md dentro del repositorio (recuerda que MD es la extensión de los ficheros Markdown) y documenta en su interior todos los pasos que vas realizando para crear un repositorio, etc. Puedes añadir fotos o lo que creas conveniente**

_Para crear el documento readme.md, lo que he hecho ha sido ir a la ruta del repositorio y desde el explorador de Windows crear el fichero readme.md_

ficheroreadme

_Para comprobar que el fichero está en la carpeta podemos usar el comando ls en la carpeta del repositorio_

Capturals


**1.3 – Añade el fichero que acabamos de añadir al repositorio al staging area, visualiza el estado del repositorio (con git status) y haz un snapshot (commit) del fichero hacía nuestro repositorio local. ¿En que “file status lifecycle” se encuentra el fichero?**

_Al realizar un git status el fichero se encuentra cargado en el staging area_

capturaejercicio1.3

**1.4 – Intenta subir los ficheros al repositorio remoto mediante al comando git push ¿Imaginas que está pasando? (si no lo sabes aún no te preocupes)**

_Al intentar subir el fichero me indica que no tengo ningún repositorio vinculado_

**1.5 – Ejecuta el comando git remote –v e investiga porque no nos aparece nada**

_No aparece nada debido a que no hemos vinculado el repositorio con el repositorio remoto._

**1.6 – Crea un repositorio remoto llamado repo01, asócialo a tu repositorio local**



**1.7 – Vuelve a ejecutar el comando git remote –v nuevamente y explica el porque ahora si que aparece**

1.5

**1.8 – Sube los cambios que hemos subido al snapshot local (commit) hacía al repositorio remoto**


1.8


**1.9 – Ves al repositorio remoto (en este caso GitHub) y comprueba que se haya realizado el commit correctamente y observa que pasa en el repositorio ¿Observas algo peculiar?**

_Si se han subido todos los ficheros al realizar el pull_

https://github.com/Ericpinasmuntane/REPO01.git
