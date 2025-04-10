<h1>Added</h1>

-v0.1 añade todo el contenido base, script, carpetas, gitignore

-v0.2 añade recuperacion.md para resumir la recuperacion del directorio borrado

-v0.3 añade archivo de workflow validate.yml y badge de estado en readme.md

-v0.4 añade resources y contenido dentro y rebase.md con información sobre rebases realizados en commits

<h1>Changed</h1>

-v0.1 se modifica el archivo gitignore para que funcione como se necesita

-v0.2 se modifica el script

-v0.3 se modifica el script según resultados de shellcheck y se modifica validate.yml

-v0.4 se modifica el script para refinar su uso y comportamiento con shellcheck

<h1>Fixed</h1>

-v0.1 se ignora correctamente .logs y .tmps

-v0.2 la ejecución del script ya no borra el directorio

-v0.3 arregla el workflow para detectar errores de sintaxis y comportarse de manera esperada

-v0.4 shellcheck ya no devuelve estado de "info" sobre script que al arreglarlo causaba el funcionamiento defectuoso del script
