# Sistema De Control de Versiones (git)

_Provee mecanismos que permite manejar de forma ordenada a los cambios que ocurren en distintas versiones de un proyecto._

## Uso del sistema de control de versiones (git)

### Inicalizar el Repositorio de Git

```bash
git init
```

### Agregar archivos al repositorio

```bash
git add .
```

### Commitear los cambios

```bash
git commit -m "mensaje"
```

### Verificar los cambios

```bash
git status
```

### Historial de cambios

```bash
git log
```

### Remover el commit

```bash
git rm -- commit_id
```

### Regresar a una version anterior

```bash
git reset -- commit_id
```

### Crear Rama

```bash
git branch nombre_rama
```

### Fusionar Cambios

```bash
git merge nombre_rama
```

### Clonar un repositorio

```bash
git clone
```

### Subir cambios

```bash
git push
```

### Actualizar cambios

```bash
git pull
```

### Visualizar el estado del repos en la nube

```bash
git remote -v
```

### ❗importante para el uso de git

##### Rama principal: master o main

##### Rama de desarrollo: develop

----------------------------------------------------------------

## Git Flow

_Gitflow es un modelo alternativo de creación de ramas en Git en el que se utilizan ramas de función y varias ramas principales_

![gitFlow](https://wac-cdn.atlassian.com/dam/jcr:cc0b526e-adb7-4d45-874e-9bcea9898b4a/04%20Hotfix%20branches.svg?cdnVersion=472)

---

## Pull Request

_Unir Ramas(branches) en una sola de manera Formal y Ordenada_

![pullRequest](https://www.vantage-ai.com/hubfs/Pull%20Request%20Attlasian.png)

### Prefijos

- `feat:""` nueva caracteristica
- `fix:""` corregir un error
- `style:""` cambios de estilo
- `test:""` agregar pruebas