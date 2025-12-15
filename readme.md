# Git Bash
## Comandos
### git init
- Es usado para inicializar un repositorio remoto en la carpeta donde se encuentra el proyecto.

### git add
- Se usa para añadir archivos al commit que se va a realizar al repositorio

### git commit
- Cuando se va a hacer el commit a subir se usa este comando y se introduce un mensaje que se va a ver al momento de hacer el push

### git push
- Este comando envía el commit al repositorio para que pueda ser visto junto con el mensaje que se introduce al momento de ejecutar `git commit`

# Proceso paso a paso para usar Git Bash
- Primero, en la carpeta donde tenemos nuestro proyecto, usamos `git init` para inicializar nuestro repositorio remoto.
- Tras esto podemos empezar a hacer los cambios que queramos en nuestro proyecto.
- Una vez terminemos todos nuestros cambios, ejecutamos el comando `git status` para ver cuáles son los archivos que tenemos ya añadidos o no; en caso de no tener algunos archivos añadidos, podemos usar `git add <nombre del archivo>` para un archivo en específico o `git add *` para añadir todos los archivos actuales.
- Después de esto, usamos el comando `git commit -m <mensaje>` para hacer el commit que vamos a subir a GitHub.
- Una vez terminados todos estos pasos, creamos nuestro repositorio y lo conectamos usando el comando `git remote add <url del repositorio>`
- Cuando ya tenemos nuestro repositorio remoto conectado, podemos ya usar el comando `git push` para subir nuestros cambios al repositorio con los cambios staged en el `git commit` y el mensaje que escribimos en este mismo.
