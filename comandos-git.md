# Comandos Git

1. Crear una rama de trabajo
    ```
    git checkout -b <branch-name>
    ```

2. Descarga los cambios desde repositorio remoto a mi repositorio local
    ```
    git pull
    ```

3. Agrega los cambios para ser enviados al commit.
    ```
    git add <filename or path>
    ```

4. Crear nueva version (Commit)
    ```
    git commit
    ```
5. Sube mis cambios al repositorio remoto
    ```
    git push
    ```

6. Integrar dos ramas o commits
    ```
    git merge
    ```

# Inicializar Configuracion

1. Agregar Author para los Commits.
```
git config --global user.name "<su-nombre>"
```

2. Agregar email para los Commits.
```
git config --global user.email "<su-correo>"
```