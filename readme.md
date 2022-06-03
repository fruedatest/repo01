# 📘Ejercicio 1 GIT📘
* Creación de directorio local llamado repo01 e iniciar el repositorio en local:
> $ mkdir repo01
 
> $ cd repo01
 
* Añadir documento llamado readme.md y documentar en su interior los pasos a realizar para crear el repositorio:
 
> $ nano readme.md
 
* Añade el fichero al staging area y haz un snapshot hacia el directorio en local:
 
> $ git add readme.md
 
> $ git commit -m "primerCommit"
 
* Crea el repositorio remoto llamado repo01, asocialo a tu repositorio local y sube los cambios al repositorio local:

> git remote -v

>git remote add origin https://github.com/fruedatest/repo01.git

> git push -u origin main