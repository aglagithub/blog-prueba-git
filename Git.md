Inatalación y configuración:

Descargar git: 
- Ejecutar programa: 
  - config por default +
  -Windpws termina
  - Use visual studio code
  - override the

configuracion
git config --global user.name "tu nombre" # configurar el nombre de usuario
git config --global user.email tucorreo@correo.com # configurar el correo electrónico
git config --global core.editor "code --wait" # configurar el editor de texto
git config --global core.autocrlf # [true|input] # configurar el formato de los archivos: windows:true, mac o linux: false
git config --global -e # editar el archivo de configuración global
git config --list # ver la configuración global
git config -h # ver la ayuda de la configuración
git config --global init.defaultBranch main # Cambiar la rama de master a main

Uso: 
inicializacion:
git init (crea archivo oculto .git)
git status (indica es estado del repositorio)
Añadido de archivos:
git add. (añade todos los archivos al staging area)
git commit -m "Mensaje" (sube archivos al repo local)
git cimmit -am "Mensaje"(push y commit en un solo comnado)

 
Ver indormacion de commits:
git lom "Mensaje"
git log --oneline (version corta)


Creación y subida e archivos al repositorio
git remote add origin https://github.com/aglagithub/blog-prueba-git.git
git branch -M main (solo si no se ha inidcado la rama)
git push -u origin main /**/ solo la primera vez
