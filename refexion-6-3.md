1. Un "conflicto de merge" es un evento que ocurre cuando Git intenta combinar dos ramas pero encuentra que ambas han sido modificadas
distintamente en las mismas líneas, y no puede decidir cuál versión mantener.

2. "<<<<<<<< HEAD" - marca el incio de la versión de la rama actual.
"========" - separador de las dos versiones conflictivas. Anterior a ello es la actual, y posterior es la otra rama que se pretende integrar.
">>>>>>>> rama" - marca el final de la versión de la rama que hemos intendado combinar, cambiando "rama" por el nombre de la rama.

3. Usar commits pequeños y regulares con descripciones específicas. 
Hacer merges regulares para mantener sincronización. 
Comunicar qué cambios se han hecho y qué archivos han sido modificados. 
Evitar que varias personas hagan cambios en el mismo archivo.
Realizar revisiones de nuestro código, asegurando que cualquier cambio es coherente con el resto del proyecto. 
