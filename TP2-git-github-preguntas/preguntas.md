# Guía de Git y GitHub

## ¿Qué es GitHub?
GitHub es una plataforma de desarrollo colaborativo basada en Git que permite almacenar, gestionar y compartir código fuente. Facilita el trabajo en equipo mediante herramientas como control de versiones, issues y pull requests.

## ¿Cómo crear un repositorio en GitHub?
1. Iniciar sesión en GitHub.
2. Hacer clic en el botón "+" en la esquina superior derecha y seleccionar "New repository".
3. Asignar un nombre al repositorio y elegir si será público o privado.
4. Opcionalmente, agregar un README, .gitignore o licencia.
5. Hacer clic en "Create repository".

## ¿Cómo crear una rama en Git?
```sh
git branch nombre-rama
```

## ¿Cómo cambiar a una rama en Git?
```sh
git checkout nombre-rama
```
O con la nueva sintaxis:
```sh
git switch nombre-rama
```

## ¿Cómo fusionar ramas en Git?
```sh
git checkout main
git merge nombre-rama
```

## ¿Cómo crear un commit en Git?
```sh
git add .
git commit -m "Mensaje del commit"
```

## ¿Cómo enviar un commit a GitHub?
```sh
git push origin nombre-rama
```

## ¿Qué es un repositorio remoto?
Un repositorio remoto es una versión alojada en un servidor de un repositorio local de Git, accesible por varios colaboradores.

## ¿Cómo agregar un repositorio remoto a Git?
```sh
git remote add origin URL_DEL_REPOSITORIO
```

## ¿Cómo empujar cambios a un repositorio remoto?
```sh
git push origin nombre-rama
```

## ¿Cómo tirar de cambios de un repositorio remoto?
```sh
git pull origin nombre-rama
```

## ¿Qué es un fork de repositorio?
Un fork es una copia de un repositorio en la cuenta de un usuario, permitiendo modificarlo sin afectar el original.

## ¿Cómo crear un fork de un repositorio?
1. Ir al repositorio en GitHub.
2. Hacer clic en el botón "Fork" en la parte superior derecha.

## ¿Cómo enviar una solicitud de extracción (pull request) a un repositorio?
1. Subir los cambios a la rama en tu fork.
2. Ir al repositorio original y hacer clic en "New pull request".
3. Seleccionar la rama fuente y la rama de destino.
4. Escribir una descripción y enviar la solicitud.

## ¿Cómo aceptar una solicitud de extracción?
1. Ir a la sección "Pull requests" del repositorio.
2. Revisar los cambios y hacer clic en "Merge pull request".

## ¿Qué es una etiqueta en Git?
Las etiquetas (tags) marcan versiones específicas del código en el historial de Git.

## ¿Cómo crear una etiqueta en Git?
```sh
git tag -a v1.0 -m "Versión 1.0"
```

## ¿Cómo enviar una etiqueta a GitHub?
```sh
git push origin v1.0
```

## ¿Qué es un historial de Git?
El historial de Git muestra todos los commits realizados en un repositorio.

## ¿Cómo ver el historial de Git?
```sh
git log
```

## ¿Cómo buscar en el historial de Git?
```sh
git log --grep="palabra clave"
```

## ¿Cómo borrar el historial de Git?
Git no permite borrar históricos directamente, pero se puede reescribir:
```sh
git rebase -i HEAD~n
```

## ¿Qué es un repositorio privado en GitHub?
Un repositorio privado solo es accesible para los usuarios autorizados.

## ¿Cómo crear un repositorio privado en GitHub?
Al crear un repositorio, seleccionar la opción "Private".

## ¿Cómo invitar a alguien a un repositorio privado en GitHub?
1. Ir a "Settings" > "Manage access".
2. Hacer clic en "Invite a collaborator".

## ¿Qué es un repositorio público en GitHub?
Un repositorio público es accesible para cualquier usuario de GitHub.

## ¿Cómo crear un repositorio público en GitHub?
Al crear un repositorio, seleccionar la opción "Public".

## ¿Cómo compartir un repositorio público en GitHub?
Compartiendo la URL del repositorio.

---
