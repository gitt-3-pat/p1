# Práctica 1
¡Hola! Este es el repositorio para la primera práctica de **PAT** del curso. Es esta, se nos pedía que nos familiarizásemos con el entorno y los comandos de Git y GitHub. Para ello, se siguió el ejemplo explicado en clase, haciendo uso de una serie de comandos e instalando en el entorno del ordenador los programas pertinentes.

## Git y Códigos
En primer lugar, los comandos que se han usado en esta práctica son:
- `git clone` el cual sirve para duplicar un repositorio localmente para poder trabajar sobre él.
    >@AlvaroGonzalez05 ➜ /workspaces $ git clone https://github.com/gitt-3-pat/p1-Alvaro
    Cloning into 'p1-Alvaro'...
    remote: Enumerating objects: 6, done.
    remote: Counting objects: 100% (1/1), done.
    remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 5
    Receiving objects: 100% (6/6), done.
    
- `git status` muestra el estado actual de los archivos del repositorio.
    >@AlvaroGonzalez05 ➜ /workspaces/p1-Alvaro (main) $ git status
    On branch main
    Your branch is ahead of 'origin/main' by 1 commit.
      (use "git push" to publish your local commits)
    
    nothing to commit, working tree clean

- `git add` se usa para seleccionar los archivos que se quieren añadir al próximo commit al main.
    >@AlvaroGonzalez05 ➜ /workspaces/p1-Alvaro (feat/add-body) $ git add .
    origin feat/add-body

- `git commit` sirve para confirmar los cambios realizados.
    >@AlvaroGonzalez05 ➜ /workspaces/p1-Alvaro (main) $ git commit -m "feat: homepage"
    On branch main
    Your branch is ahead of 'origin/main' by 1 commit.
      (use "git push" to publish your local commits)
    nothing to commit, working tree clean

- `git push` se utiliza para mandar los cambios, una vez commiteados, al repositorio remoto de git.
    >@AlvaroGonzalez05 ➜ /workspaces/p1-Alvaro (main) $ git push origin main
    Enumerating objects: 5, done.
    Counting objects: 100% (5/5), done.
    Delta compression using up to 2 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (4/4), 407 bytes | 407.00 KiB/s, done.
    Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/AlvaroGonzalez05/p1-Alvaro
       07720b5..3ea4a2d  main -> main

- `git checkout` es el comando que se utiliza para moverse entre las ramas de un repositorio. Lo he utilizado para crear una rama nueva en la que hacer cambios en el fichero "index.hmtl", para luego commitearlos.
    >@AlvaroGonzalez05 ➜ /workspaces/p1-Alvaro (main) $ git checkout -b feat/add-body
    Switched to a new branch 'feat/add-body'

## Entorno
Se ha descargado tanto Java 17 como Maven, conforme a los requisitos de la práctica, tal y como se muestra a continuación:
![image](https://github.com/AlvaroGonzalez05/p1-Alvaro/assets/116951010/4e63df0a-d03c-4b06-a780-0a58a843ed55)

Además ya se tenía instalado VsCode en este dispositivo, por lo tanto sólo hubo que instalarse IntelliJ.

![image](https://github.com/AlvaroGonzalez05/p1-Alvaro/assets/116951010/dd7228cd-0155-40a8-a2b7-db08fd666769)![image](https://github.com/AlvaroGonzalez05/p1-Alvaro/assets/116951010/25c36c30-ff8d-49d5-a864-f10b98875f97)
