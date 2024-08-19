# Este será un pequeño tutorial de Git

### Qué es Git
Imagina que estás escribiendo una historia en un cuaderno. A veces, quieres guardar una copia de lo que has escrito hasta ahora, por si acaso quieres volver a esa versión más tarde. Git es como una máquina del tiempo para tu cuaderno. Te permite guardar diferentes versiones de tu historia y volver a ellas cuando quieras.

### Qué es Github
Ahora, imagina que quieres compartir tu historia con tus amigos para que ellos también puedan leerla y hacer cambios. GitHub es como una biblioteca en internet donde puedes guardar tu cuaderno y tus amigos pueden verlo y trabajar en él contigo.

## Comandos de Git

#### Inicializar un repositorio de git
```bash
git init
```
Este comando sirve para decirle a Git que quieres empezar a usar la máquina del tiempo en tu cuaderno. Es como decir "¡Hey, Git! Empieza a recordar las versiones de mi historia desde ahora."

#### Agregar un cambio a la zona de "staging"
```bash
git add <ruta-del-archivo>
```
O, si quieres agregar todos los cambios:
```bash
git add .
```
Este comando es como poner una marca en tu cuaderno diciendo "Quiero recordar esta parte de mi historia". Puedes elegir qué partes quieres recordar.

#### Guardar los cambios en el repositorio
```bash
git commit -m "Mensaje describiendo el cambio"
```
Este comando es como tomar una foto de tu cuaderno en el momento en que lo usas. El mensaje es una pequeña nota para recordar qué cambios hiciste en esa versión.

#### Ver el historial de cambios
```bash
git log
```
Este comando te muestra todas las fotos que has tomado de tu cuaderno, para que puedas ver cómo ha cambiado tu historia con el tiempo.


## ¿Qué es un PR?
Un PR es una vaina loca que me lleva a la gloria