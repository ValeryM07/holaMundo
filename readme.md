# GIT

## Comandos:

### Comandos globales:

+ git --version:
    Me muestra mi versión actual de git
+ git config --global user.name "usuario de git"
    Asigna mi usuario a mi compu.
+ git config --global user.email "correo que corresponde al usuario"
+ git config user.name 
    Nos enseña el usuario actual.
+ git config user.email
    Nos enseña el correo del usuario actual
+ ls 
    Nos muestra la lista de archivos en la carpeta que estamos

### Comandos de repositorio:

+ git init
    Inicia el repositorio (agrega la palabra master en celeste a la ruta)
+ git status
    Nos muestra el estado de todos nuestros archivos.
    + rojo: Untracked
    + verde: Stage
+ git add
    (Incluir nombre si solo quiero 1)
+ git add .
    Agrega a Stage todos los archivos
+ git commit -m "descripción"
    Agrega al repositorio todo lo que está en Stage con un nombre y marca de tiempo
+ git log
    Nos muestra el historial e información de los commit
### Comandos de repositorio remoto (githug):
+ git remote add origin https://github.com/ValeryM07/holaMundo.git
    Agrega con el nombre origin la ruta remota
+ git push -u origin
    Empuja la rama master a la ruta remota