# Comandos de git

## Comando para ver la versión de git

- git -v
- git --version

## Comandos para configuración inicial de git

- git config --global user.name "Your name"
- git config --global user.email "Your email"

## Comando para editar o ver la configuracion de git

Para salir del edit ctrl + o y Ctrl + X
y si es VIM esc y :wq

- git config --global --edit
- git config --global --list

## Como iniciar git en un directorio

- git init

## Comando para saber el estado de nuestros archivos

- git status

## Comando para listar las versiones de mi proyecto

- git log
- git log --oneline

## Comando para cambiar de versión

- git checkout <Id del commit o nombre de la rama>

## Pasos para crear un versión de nuestro código

1. Agregar todos los archivos al commit

- git add .
- git add \*.js
- git add styles.css

2. Tomar la foto del código (Crear una nueva versión)

- git commit -m "Nombre del commit"
