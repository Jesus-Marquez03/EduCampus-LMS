# Guía de contribución

Esta guía explica cómo contribuir al proyecto de forma ordenada usando Git y GitHub.

## Cómo crear una rama de trabajo

Siempre hay que partir desde la rama develop actualizada:

git checkout develop
git pull origin develop
git checkout -b nombre-de-la-rama

## Cómo nombrar las ramas

El nombre debe ser claro y relacionado con lo que se va a trabajar.
Algunos ejemplos:

- feature/modulo-usuarios
- fix/error-en-notas
- docs/guia-instalacion

## Cómo escribir mensajes de commit

El mensaje debe explicar qué se hizo de forma corta y clara.
Formato recomendado:

tipo: descripción breve

Ejemplos:
- docs: Se agrega guía de instalación
- fix: Se corrige cálculo de notas
- feat: Se agrega módulo de reportes

## Cómo crear un Pull Request

1. Sube tu rama con: git push origin nombre-de-la-rama
2. Ve al repositorio en GitHub
3. Haz clic en "Compare & pull request"
4. Escribe un título y una descripción del cambio
5. Asigna un revisor y crea el PR

## Cómo solicitar revisión

En el Pull Request, en la sección "Reviewers", selecciona a la persona
que va a revisar tu código. Espera su aprobación antes de hacer merge.

## Qué hacer si hay un conflicto

1. Abre el archivo con conflicto
2. Busca las marcas <<<<<<<, ======= y >>>>>>>
3. Lee las dos versiones y decide cuál queda o cómo se combinan
4. Borra las marcas y deja el archivo limpio
5. Haz git add y continúa con el proceso

## Nota adicional

Es importante mantener el repositorio organizado en todo momento.

Recuerda siempre hacer pull antes de empezar a trabajar.

Consulta al líder técnico si tienes dudas sobre el flujo de trabajo.