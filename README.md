# Clase 15

## Configuración inicial. (Solo la primera vez)

<!-- sh
git config --global user.name "Hernán Bianchimano"
git config --global user.email "hernanbianchimano@gmail.com"
 -->

 ## Verificar si todo quedó bien o si hice estas configuraciones

 <!-- sh
 git config --get-regexp user
  -->

## Crear un repositorio (Inicializar un repo)

<!-- sh
git init
 -->

 ## Areas del repositorio de GIT

 3 áreas
 
 * Working Directory (WD): Directorio de trabajo donde sevan agregando o quitando los archivos durante el desarrollo.
 * Staging Area (SA): Area de control de cambios. Area temporal/intermedia.
 * Local Repo (LR): Una caja donde voy a ir teniendo todas las fotos que vaya sacando.

 ## El estado de los archivos en el repositorio

 ## El estado de los archivos

 * untracked: Está en el WD pero GIT no les da seguimiento.
 * unmodified: Archivos que GIT ya está siguiendo y con respecto al WD, no han sido modificados.
 * modified: Archivos que se encuentran en el repositorio (están siendo seguidos por GIT) pero difieren con lo que se encuentra actualmente en el WD.
 * staged: Archivos que están en el area temporal/intermedia.

 ## Saber estado actual de los archivos

<!-- 
git status
 -->

 ## Voy a poder mover los archivos de WD al SA

 <!-- sh
 git add <nombre-archivo>
 git add index.html
 git add README.md css/estilos.css
 git add .  (agrego todos los archivos U o M) -->

 ## La historia de commits (La caja de fotos)

 <!--sh
 git log # La historia de commit detallada
 git log --oneline # Historia resumida
  
 Nota: si la consola queda bloqueada y no puedo salir del listado
 tengo que apretar la tecla q (quit).
  -->
