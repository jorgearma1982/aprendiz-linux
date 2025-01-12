# Domina la Edición y Deshacer Texto en Vim - Lección 2 del vimtutor

## Introducción

Hoy seguimos con la **Lección 2 del vimtutor**, en la que aprenderás a borrar texto de manera avanzada, entender los
mandatos y objetos, y deshacer cambios para trabajar con confianza.

## Prácticas

### Práctica 2: Comandos de borrado avanzado

Comenzamos con los comandos para borrar texto. En la **Lección 1** aprendimos `x` para borrar un carácter, pero
aquí llevamos el borrado al siguiente nivel:

* `dw` borra desde el cursor hasta el final de una palabra.
* `d$` elimina desde el cursor hasta el final de la línea.
* `dd` borra una línea completa.

Estos comandos son rápidos y potentes. ¡Mira cómo funcionan! 🧹

### Práctica 3: Mandatos y objetos

Ahora vamos a entender cómo los mandatos y objetos trabajan juntos para que edites más rápido. En Vim, los
**mandatos** como `d` (borrar) o `y` (copiar) combinan con **objetos** para definir qué editar.

Por ejemplo:

* `d` + `w` (palabra) = `dw` borra hasta el final de la palabra.
* `d` + `$` (línea) = `d$` borra hasta el final de la línea.

Lo mejor es que esta lógica aplica a muchos comandos en Vim. Es como armar bloques de Lego. 🧩

### **Escena 4: El comando deshacer (Duración: 1.5 minutos)**

Y por supuesto, nadie es perfecto. Aquí entra el comando deshacer:

* Usa `u` para deshacer el último cambio.
* Si necesitas rehacer algo que deshiciste, usa `Ctrl + r`.

¡Práctico y fácil de usar! 🔄

## Conclusión

¡Y eso es todo por la **Lección 2** del vimtutor! Hoy aprendiste a usar comandos avanzados para borrar, combinaste
mandatos y objetos, y dominaste el comando deshacer para trabajar con confianza. 🚀

Tu reto práctico es crear un archivo de prueba, editarlo con los comandos aprendidos y deshacer cualquier error.
