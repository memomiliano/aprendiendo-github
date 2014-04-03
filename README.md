Aprendiendo GitHub
==================

Este es un ejemplo para aprender GIT.
Voy a anotar algunos comandos para no olvidarlos

<h3>INICIO UN NUEVO PROYECTO</h3>
<div class="highlight highlight-bash"><pre>git init</pre></div>

<h3>CREAR UN NUEVO ARCHIVO</h3>
<div class="highlight highlight-bash"><pre>touch "nombredelarchivo.extension"</pre></div>

<h3>AÑADIR EL ARCHIVO CREADO A MI BRANCH</h3>
<div class="highlight highlight-bash"><pre>git add "nombredelarchivo.extension"</pre></div>

<h3>CONOCER EL ESTATUS DE MI PROYECTO</h3>
<div class="highlight highlight-bash"><pre>git status</pre></div>

<h3>HACER COMMIT</h3>
<div class="highlight highlight-bash"><pre>git commit -m "comentario descriptivo del commit, preferentemente haciendo alusión a los cambios realizados"</pre></div>

<h3>CONECTANDOME CON MI PROYECTO EN GITHUB</h3>
<div class="highlight highlight-bash"><pre>git remote add origen https://github.com/memomiliano/aprendiendo-github.git</pre></div>

<h3>TRAER A MI NOTEBOOK TODO EL CONTENIDO DE LA WEB</h3>
<div class="highlight highlight-bash"><pre>git pull origen master</pre></div>

<h3>SUBIR A GITHUB TODO EL CONTENIDO DE MI REPOSITORIO LOCAL</h3>
<div class="highlight highlight-bash"><pre>git push origen master</pre></div>