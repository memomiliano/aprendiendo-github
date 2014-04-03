Aprendiendo GitHub
==================

Este es un ejemplo para aprender GIT.

Voy a anotar algunos comandos para no olvidarlos

<h3>INICIO UN NUEVO PROYECTO</h3>
git init

#CREAR UN NUEVO ARCHIVO
touch "nombredelarchivo.extension"

#AÑADIR EL ARCHIVO CREADO A MI BRANCH
git add "nombredelarchivo.extension"

#CONOCER EL ESTATUS DE MI PROYECTO
git status

#HACER COMMIT
git commit -m "comentario descriptivo del commit, preferentemente haciendo alusión a los cambios realizados"

#CONECTANDOME CON MI PROYECTO EN GITHUB
git remote add origen https://github.com/memomiliano/aprendiendo-github.git

#TRAER A MI NOTEBOOK TODO EL CONTENIDO DE LA WEB
git pull origen master

#SUBIR A GITHUB TODO EL CONTENIDO DE MI REPOSITORIO LOCAL
git push origen master