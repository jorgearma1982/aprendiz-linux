# Aprende a buscar y remplazar texto en Vim con la Lección 4 del vimtutor

## Descripción

Esta es la cuarta entrega de nuestra serie sobre el **vimtutor**, donde seguimos desentrañando los secretos de Vim.
Aprenderemos a visualizar la posición actual en el archivo, aprenderemos a hacer búsquedas y sustituciones de
texto como todo un profesional.

**Lo que aprenderás:**

* **Visualizar la posición actual** en el archivo usando `Ctrl-g`.
* **Buscar** texto hacia adelante y hacia atrás.
* **Utilizar `%`** para saltar entre paréntesis o corchetes coincidentes.
* **Realizar sustituciones** con `:s` para modificar texto rápidamente.

Prepárate para potenciar tu eficiencia en la navegación y edición con estas herramientas esenciales. Al final,
te plantearemos un reto práctico para consolidar lo aprendido.

## Prácticas

### Práctica 1. Control de posición con `Ctrl-g`

Comencemos con `Ctrl-g`. Este comando muestra la posición actual del cursor en el archivo. Si presionas `Ctrl-g`,
aparecerá en la parte inferior información sobre la línea y columna donde estás.

Esto es súper útil para orientarte en archivos largos.

¡Haz la prueba en tu terminal!"

### Práctica 2: Búsqueda hacia adelante y atrás

Ahora, pasemos a las búsquedas. Para buscar hacia adelante en el archivo, usa `/` seguido del texto que buscas.

Para buscar hacia atrás, utiliza `?`. Una vez que encuentres lo que necesitas, puedes moverte entre las
coincidencias con `n` para adelante y `N` para atrás.

Estas herramientas te ahorrarán mucho tiempo al navegar por grandes bloques de texto.

### Práctica 3: Búsqueda con `%`

El comando `%` es perfecto para saltar entre paréntesis o corchetes coincidentes.

Si tienes una función rodeada por estos símbolos, `%` te llevará del inicio al final y viceversa.

Es ideal para revisar bloques de código o expresiones complejas.

### Práctica 4: Realización de sustituciones

Finalmente, las sustituciones. Con `:s`, puedes reemplazar texto rápidamente. Por ejemplo, `:s/viejo/nuevo/`
cambiará la primera aparición de 'viejo' por 'nuevo' en la línea actual.

Si quieres cambiar todas las apariciones en el archivo, usa `:%s/viejo/nuevo/g`.

¡Así de poderoso es este comando!"

## Conclusiones

Y ahí lo tienes, los comandos esenciales de la lección 4. Ahora te reto a practicar:

* Usa `Ctrl-g` para orientarte en tus archivos.
* Prueba búsquedas con `/` y `?`, y encuentra paréntesis coincidentes con `%`.
* Haz sustituciones en tus textos usando `:s`.

Nos vemos en la próxima lección del vimtutor.
