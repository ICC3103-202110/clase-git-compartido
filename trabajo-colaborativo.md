# Trabajo colaborativo con git

1. Mantener actualizada las ramas
`git pull`

2. Actualizar mi rama con los últimos cambios de master (después del pull)
`git rebase master <mi_rama>`

3. Conflictos
`git status` -> qué archivos tienen Conflictos
editar los archivos borrando las líneas <<<<<, =====, >>>>>
`git add <arhivos_editados>`
`git rebase --continue` -> cambiar mensaje commit?

4. Subir actualización rama
`git push -f`

Convenciones de Angular: https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit