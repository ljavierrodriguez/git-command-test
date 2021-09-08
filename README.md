### Inicializar Proyecto de GIT 

    $ git init

### Preparar archivos a gregar al repositorio

    $ git add <file>
    $ git add -A
    $ git add .
    $ git add *

### Guardar Archivos en el repositorio

    $ git commit
    $ git commit -m "Guardando README.md"


### Retroceder Cambios Realizados
    1. Antes de hacer git add
    2. Despues de hacer git add
    
    $ git restore <file>
    $ git restore --staged <file>

### Crear una Rama

    $ git branch <branch-name>

### Mostrar todas las ramas(branch) existentes

    $ git branch

### Cambiar de Rama (branch)

    $ git checkout <branch>

### Reset HEAD

    $ git reset --soft <hash>

### Unir ramas(branch) con merge

    $ git merge <rama-origen> <rama-destino>

### Repositorio Remoto

    $ git remote add <name> <url-repo-remoto>
    $ git remote set-url <name> <url-repo-remoto>
    $ git remote rm <name>

### Subir los cambios al repositorio remoto

    $ git push <remote> <branch>

### Bajar los cambios al repositorio local

    $ git pull <remote> <branch>