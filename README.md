# git-demo

## instalacion

## comandos

### git config

```
git config --global/--local user.name "<nombre>"
git config --global/--local user.email "<email>"
```

### git clone

```
git clone <repo>
```

### git branch / git checkout

```
git branch <nombre> (crea la branch)
git branch -M <nombre> (se mueve a la branch indicada)
git branch -D <nombre> (elimina la brancha indicada)
```

```
git checkout <nombre> (se mueve a la branch indicada)
git checkout <nombre> (se crea la branch)
```

### git status
```
git status (Se muestra el estado de los archivos)
```

### git add
```
git add <nombre> (se agrega el archivo para commitear)
git add . (se agregan todos los archivos modificados para commitear)
```

### git commit
```
git commit -m <mensaje> (se realiza el commit sobre la branch)
git commit --amend [-m <mensaje] (se corrige el ultimo commit)
```

### git reset
```
git reset --soft (se vuelve al commit anterior manteniendo los cambios)
git reset --hard (se vuelve al commit anterior eliminando los cambios del ultimo commit)
```

### git log

```
git log (muestra el historial de commits con fechas y autores)
```

### git stash
```
git stash (guarda todos los cambios agregados y no agregados en el stash y limpia la rama)
git stash apply (aplica todos los cambios en el top de la pila de stash)
```

### git pull
### git push

## Nombres de branch y mensajes de commit

### Main
### Development
### Fix
### Change Request
### Technical Task


## Control de Versiones

### Pull Requests
