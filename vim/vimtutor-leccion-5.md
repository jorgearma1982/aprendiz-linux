# Ejecuta Comandos Externos y Domina la Gestión de Archivos en Vim con la lección 5 del vimtutor

## Descripción

En esta quinta entrega de nuestra serie del vimtutor exploraremos cómo ejecutar comandos externos y mejorar la
gestión de tus archivos directamente desde Vim.

Te mostraremos a ejecutar comandos de la terminal sin salir de vim, que de por si ya es difícil para los
principiantes, veremos como escribir y leer de forma selectiva.

Lo que aprenderás:

* Ejecutar comandos externos con `:!comando` 💻
* Guardar secciones específicas de un archivo con `:w rango archivo.txt` ✂️
* Recuperar contenido de otros archivos con `:r archivo.txt` 📥

## Prácticas

### Práctica 2: Ejecutando Comandos Externos

¿Alguna vez has necesitado ejecutar un comando del sistema sin salir de Vim? Con `:!comando`, puedes hacerlo
directamente. Por ejemplo, `:!ls` mostrará el contenido de tu directorio actual.

### Práctica 3: Guardar Parte del Archivo

¿Quieres guardar solo una parte específica de tu archivo? Con `:w`, puedes hacerlo. Por ejemplo,
`:w 1,5 parcial.txt` guardará las primeras cinco líneas en un nuevo archivo llamado `parcial.txt`."

### Práctica 4: Recuperando Contenido de Otros Archivos

Puedes insertar contenido de otro archivo en tu documento actual usando `:r archivo.txt`. Esto es muy útil cuando
necesitas integrar información adicional sin salir de Vim.

## Conclusiones

Eso es todo por hoy. Ahora tienes nuevas herramientas para gestionar archivos y ejecutar comandos externos en Vim.
Recuerda practicar y compartir tus avances. ¡Nos vemos en la próxima lección!"
