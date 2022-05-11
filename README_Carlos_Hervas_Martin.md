Este readme contiene información sobre los comandos usados:

1) Inicio un directorio: 
$ mkdir curso_git_github

2) Accedo al directorio:
$ cd curso_git_github

3) Inicio el repositorio:
$ git init

4) Clono el repositorio de GitHub:
$ git clone https://github.com/KeepCoding-FAM-Expleo-2022/curso_git_github.git

5) Creo un nuevo README vacío:
$ touch README_Carlos_Hervas_Martin.md

6) Añado información a ese README con 'echo'

7) Hago stage de los cambios (de todos los archivos de la carpeta):
$ git add .

8) Compruebo que se ha añadido a stage con:
$ git status

9) Hago commit de los cambios en stage:
$ git commit -m "Se añade el fichero README_Carlos_Hervas_Martin.md"

10) Compruebo si el commit se ha hecho correctamente con:
$ git log --oneline

11) Hago push del commit:
$ git push origin main --force

12) Compruebo el repositorio en GitHub para ver que mi archivo está sincronizado correctamente