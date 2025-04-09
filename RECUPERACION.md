-Qué error simulaste

He simulado un error en la ejecución de un scripts debido a estar mal escrito y no realizar
lo esperado (borraba el contenido de la carpeta y la carpeta en local, cuando solo quería que
borrase el contenido de la carpeta)

-Que comandos usaste para recuperar el archivo

He usado el comando "git reftlog" para volver a un commit previo al error y luego los comandos
"git checkout hash del commit" para cambiar a dicho commit, he realizado los cambios y
ejecutado los comandos "git branch nombre de nueva rama" "git checkout main" y
<git merge nombre de nueva rama" para crear la rama en la que he realizado los cambios,
volver a main y mergear los cambios en main y poder subirlos con "git push". A lo largo de
la ejecución me he ayudado de otros comandos como "git status" "ls" o el propio "git reftlog"

-Que aprendiste de la experiencia

He aprendido a saber como manejar situaciones de recuperación de archivos en repositorios de
diferente formas y he aplicado una de ellas, así como he solucionado problemas relacionados
con el archivo "errores.sh" que hacían que su ejecución no fuera la deseada.
