He empezado con el comando "git rebase -i" para abrir el editor interactivo donde
puedo elegir que hacer con los commits.

Como se ha explicado en el PDF el primer commit le pongo el comando reword, el segundo
lo dejo vacio, el tercero squash para que se combine con el anterior y el cuarto
commit tambien reword

Guardo los cambios en el editor y se me van abriendo en orden todos los comandos de
cada commit, de esta manera puedo hacer las tareas de cada uno de dichos comandos
(cambiar nombres de mensajes, fusionar y asignar nuevo nombre)

Reviso el log para ver los cambios realizados y ejecuto un git push --force para
guardar los cambios de estos commits ya realizados previamente en el repositorio
