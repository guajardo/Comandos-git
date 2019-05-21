Git Commands and Terminal / Comandos de GIT y Terminal
============

_A list of commonly used Git and Terminal commands_

*Una pequeña lista de los comandos mas utilizados en Git y la Terminal*

--

### Terminal Commands / Comandos de la Terminal

| Command | Description | Descripción |
| ------- | ----------- | ------------ |
| `cd [rute]` | To change directory | Cambia el directorio |
| `mkdir [name]` | Make directory | Crea una nueva carpeta |
| `ls -a` | List information about the files | Lista los archivos del directorio |
| `clear` | clear the terminal screen | Limpia la Terminal |
| `Touch [name.txt]` | create a empty file | Crea un archivo vacio |
| `rm [file]` | remove files | Elimina un archivo |
| `rm -rf [dir]` | remove directories | Elimina una carpeta |
| `pwd` | Print name of current/working directory | Muestra el directorio donde nos encontramos |
| `mv` | move (rename) files | Mueve o renombra archivos |
| `cat [name.txt]` | Concatenate files and print on the standard output | Vista previa del contenido del archivo |
| `sudo` | execute a command as another user | Ejecuta un commando como administrador |

### Config Git / Configuracion de Git

| Command | Description | Descripción |
| ------- | ----------- | ------------ |
| `git config --global user.name "name-example"` | Add a user name | Añade un nombre de usuario |
| `git config --global user.email user@example.com` | Add a email for user | Añade un correo del usuario |
| `git config --list` | List all setings | Muestra todas las configuraciones |

### Creating Projects / Creacion de proyectos

| Command | Description | Descripción |
| ------- | ----------- | ------------ |
| `git init` | Initialize a local Git repository | Inicia un repositorio local de Git |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository | Crea una copia local de un repositorio remoto |

### Basic Snapshotting / Snapshooting Basico

| Command | Description | Descripción |
| ------- | ----------- | ----------- |
| `git status` | Check status | Verifica el estatus del repositorio |
| `git add [file-name.txt]` | Add a file to the staging area | Añade un archivo al area de preparación |
| `git add .` | Add all new and changed files to the staging area | Añade todos los archivos al area de preparación |
| `git commit -m "[commit message]"` | Commit changes | Añade los archivos al repositorio |
| `git rm -r [file-name.txt]` | Remove a file (or folder) | Elimina archivos o carpetas |

### Branching & Merging / Ramas y fusionar

| Command | Description | Descripción |
| ------- | ----------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) | Lista todas las ramas |
| `git branch -a` | List all branches (local and remote) | Lista todas las ramas locales y remotas |
| `git branch [branch name]` | Create a new branch | Crea una nueva rama |
| `git branch -d [branch name]` | Delete a branch | Elimina una rama |
| `git push origin --delete [branch name]` | Delete a remote branch | Elimina una rama remota |
| `git checkout -b [branch name]` | Create a new branch and switch to it | Crea una nueva rama y cambia a ella |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it | Clona una rama remota y cambia a ella |
| `git checkout [branch name]` | Switch to a branch | Cambiar a una rama determinada |
| `git checkout -` | Switch to the branch last checked out | Cambia a la ultima rama seleccionada |
| `git checkout -- [file-name.txt]` | Discard changes to a file | Descarta los cambios de un archivo |
| `git merge [branch name]` | Merge a branch into the active branch | Fusiona una rama a la rama activa
| `git merge [source branch] [target branch]` | Merge a branch into a target branch | Fusiona una rama a una rama determinada |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects / Compartiendo y Repositorios Remotos

| Command | Description | Descripción |
| ------- | ----------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository | Envia el repositorio local a remoto |
| `git push origin --delete [branch name]` | Delete a remote branch | Elimina un repositorio remoto |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository | Hace un feth y fusiona
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository | Crea un repositorio remoto |
| `fork` | Copy a external repository | Copa un repositorio externo |
| `git remote -v` | list remote connections | Lista las conexiones remotas |

### Inspection & Comparison / Inspeccion y Comparacion

| Command | Description | Descripción |
| ------- | ----------- | ----------- |
| `git log` | View changes | Muestra los cambios en el repositorio |
| `git log --summary` | View changes (detailed) | Muestra los cambios en el repositorio detalladamente |
| `git diff [source branch] [target branch]` | Preview changes before merging | Compara los diferentes cambios |

