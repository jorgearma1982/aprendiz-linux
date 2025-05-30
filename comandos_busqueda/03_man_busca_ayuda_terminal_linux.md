# man, apropos, whatis, whereis: Busca ayuda en la terminal Linux

En este video aprenderás cómo usar herramientas básicas de búsqueda de información en Linux para encontrar
ayuda sobre comandos y conceptos directamente desde la terminal.

## 🧠 ¿Qué hace cada comando?

- **`man`**: Muestra el manual completo de un comando.
- **`whatis`**: Muestra una breve descripción de un comando.
- **`apropos`**: Busca comandos relacionados con una palabra clave o tema.
- **`whereis`**: Muestra la ruta de instalación de un comando.

## 💡 Ejemplos prácticos

### Leer el manual del comando `ls`

```bash
man ls
```

### Obtener una breve descripción de `grep`

```bash
whatis grep
```

### Buscar comandos relacionados con "copy"

```bash
apropos copy
```

### Ver la ruta del comando `grep`

```bash
whereis grep
```

## 🎯 Reto práctico

1. Usa `man` para leer la documentación de `find`.
2. Usa `whatis` con un comando que ya conozcas.
3. Usa `apropos` con una palabra como `search` o `file`.
4. Usa `whereis` para ver la ubicación de `curl`.

## 📚 Recursos adicionales

- Puedes salir del manual con la tecla `q`.
- Usa las flechas para navegar dentro del manual (`man`).
- Si no encuentras resultados con `whatis` o `apropos`, ejecuta:

```bash
sudo mandb
```

para reconstruir la base de datos del manual.

Conocer estas herramientas es clave para ser autónomo y resolver tus dudas sin salir de la terminal.
¡Sigue practicando y mejorando tu fluidez en Linux! 🚀🐧
