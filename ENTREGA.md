# Entrega del Trabajo Práctico Integrador

## Datos del participante
- Nombre y apellido: Nelson Daniel Romero
- Curso:  Introducción a Git y GitHub para la Gestión de Proyectos Digitales
- Fecha de entrega: 04/11/2026

## Enlaces
- Repositorio de GitHub: https://github.com/nedaro34/tp-integrador-git-Romero-Nelson-Daniel
- Issue: https://github.com/nedaro34/tp-integrador-git-Romero-Nelson-Daniel/issues/2
- Pull request: https://github.com/nedaro34/tp-integrador-git-Romero-Nelson-Daniel/pull/4
- Aclaración: mi rama principal se llama master

## Comandos principales utilizados

- git init
- git status
- git add
- git commit
- git log --oneline
- git remote add origin
- git remote -v
- git push
- git branch
- git switch
- git merge
- git pull



## Descripción del proceso
Inicialicé el repositorio localmente y luego cree el repositorio remoto en Github. Cree los archivos README.md y ENTREGA.md en la raíz, cree la carpeta proyecto conteniendo index.html y styles.css. Todos los archivos se encontraban vacíos. 

Vinculé el repositorio local con el repositorio remoto usando `git remote add origin`, agregué a stagin usando `git add .`, hice commit con `git commit -m` y subí el primer cambio usando `git push`.

Las ramas fueron creadas usando `git switch` y luego fusionadas con la rama master realizando `git merge`, repitiendo este ciclo múltiples veces involucrando distintas ramas.

## Dificultades encontradas
Luego de fusionar dos ramas me sucedió que borré sin querer la carpeta proyecto. En lugar de clonar el repositorio, usé `git revert` para restaurar los archivos que se encontraban en el último commit.

## Reflexión final
Git es una buena herramienta que es de mucho provecho al usarse en el desarrollo de software. Creo que su potencial no se aprovecha de la misma manera en otras áreas de la informática, pero no deja de ser una buena herramienta para llevar el control de versiones en proyectos que usen múltiples archivos y tener una especie de backup que es sencillo de realizar.