# Experiencia en el trabajo colaborativo con Git y GitHub

## Participantes simulados
- Marco Antonio (rama `main`)
- Gonzalo (rama `gonzalo`, simulada)

## Flujo de trabajo realizado

### 1. Creación del repositorio
- Se creó el repositorio en GitHub llamado `TrabajoColaborativo`.
- Se clonó el repositorio localmente y se configuró correctamente.

### 2. Creación y uso de ramas
- Se creó la rama `gonzalo` usando: `git checkout -b gonzalo`
- En esta rama se realizaron cambios como edición de archivos o creación de nuevos.

### 3. Commits realizados
- Se realizaron varios commits documentando los cambios en la rama `gonzalo`.

### 4. Merge de ramas
- Se hizo un merge de la rama `gonzalo` hacia `main` sin conflictos:
  ```bash
  - git checkout main
  - git merge gonzalo