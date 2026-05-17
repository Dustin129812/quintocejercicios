# Guía de Comandos Git
## Configuración inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "correo@example.com"
```
Ver configuración actual:
```bash
git config --list
```
# Crear repositorio
Inicializar Git:
```bash
git init
```
Clonar repositorio:
```bash
git clone URL_DEL_REPOSITORIO
```
# Estado y seguimiento
Ver estado del proyecto:
```bash
git status
```
Agregar archivo específico:
```bash
git add archivo.txt
```
Agregar todos los archivos:
```bash
git add .
```
# Commits
Crear commit:
```bash
git commit -m "mensaje del commit"
```
Agregar y commitear rápidamente:
```bash
git commit -am "mensaje"
```
Ver historial:
```bash
git log
```
Historial resumido:
```bash
git log --oneline
```
# Ramas
Ver ramas:
```bash
git branch
```
Crear rama:
```bash
git branch nombre-rama
```
Cambiar de rama:
```bash
git checkout nombre-rama
```
Crear y cambiar:
```bash
git checkout -b nombre-rama
```
Eliminar rama:
```bash
git branch -d nombre-rama
```
# Sincronización con GitHub
Conectar repositorio remoto:
```bash
git remote add origin URL
```
Ver remotos:
```bash
git remote -v
```
Subir cambios:
```bash
git push 
```
```bash
git push -u origin nombre-rama
```
Bajar cambios:
```bash
git pull 
```
```bash
git pull origin nombre-rama
```
# Actualizar repositorio
Descargar cambios sin fusionar:
```bash
git fetch
```
Fusionar ramas:
```bash
git merge nombre-rama
```
# Deshacer cambios
Quitar archivo del staging:
```bash
git restore --staged archivo.txt
```
Descartar cambios:
```bash
git restore archivo.txt
```
Volver al último commit:
```bash
git reset --hard HEAD
```
# Eliminar archivos
Eliminar archivo:
```bash
git rm archivo.txt
```
Eliminar rama remota:
```bash
git push origin --delete nombre-rama
```
# Tags
Crear tag:
```bash
git tag v1.0
```
Subir tags:
```bash
git push origin --tags
```
# Comparaciones
Ver diferencias:
```bash
git diff
```
Ver diferencias staged:
```bash
git diff --staged
```
# Stash
Guardar cambios temporales:
```bash
git stash
```
Recuperar cambios:
```bash
git stash pop
```
Ver stashes:
```bash
git stash list
```

