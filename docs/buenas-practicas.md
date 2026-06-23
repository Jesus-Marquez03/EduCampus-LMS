# Buenas prácticas

Acá se recogen algunas buenas prácticas para trabajar con Git y GitHub
de forma ordenada dentro del proyecto.

## Buenas prácticas de commits

- Haz commits pequeños, cada uno con un solo propósito.
- El mensaje debe decir claramente qué se hizo.
- No mezcles cambios de temas distintos en un mismo commit.
- Antes de hacer git add, revisa qué archivos vas a incluir.

## Buenas prácticas de ramas

- No trabajes directamente sobre main ni sobre develop.
- Crea una rama nueva para cada tarea o funcionalidad.
- Cuando termines y hagas merge, elimina la rama.
- El nombre de la rama debe describir lo que hace.

## Buenas prácticas de revisión de código

- Lee bien los cambios antes de aprobar un Pull Request.
- Si algo no está claro, comenta y pregunta, no rechaces sin explicar.
- Verifica que los cambios no rompan lo que ya estaba funcionando.

## Buenas prácticas de sincronización

- Antes de empezar a trabajar, corre git pull origin develop.
- No dejes pasar muchos días sin sincronizarte con el repositorio remoto.
- Si hay conflictos, resuélvelos con cuidado sin borrar trabajo ajeno.

## Buenas prácticas antes de integrar cambios

- Limpia los commits si tienen mensajes poco descriptivos.
- Asegúrate de que tu rama esté actualizada respecto a develop.
- Revisa que todos los archivos estén en el estado correcto antes del PR.