# 🔍 find - Aprende el comando find para buscar archivos en la terminal de Linux

Este comando permite buscar archivos y directorios desde la terminal de Linux, de forma recursiva y con
múltiples criterios.

## Sintaxis básica

```bash
find [ruta] [opciones]
```

- Si no se especifica ruta, se asume la actual (`.`).
- Las opciones permiten definir cómo se hará la búsqueda.

## Ejemplos

### Buscar todo en el directorio actual

```bash
find .
```

Lista todos los archivos y carpetas desde el directorio actual hacia abajo.

### Buscar archivo por nombre exacto

```bash
find . -name archivo.txt
```

Busca `archivo.txt` en el árbol de directorios actual. Es sensible a mayúsculas.

### Buscar archivo ignorando mayúsculas

```bash
find . -iname archivo.txt
```

Busca archivos como `archivo.txt`, `Archivo.txt`, `ARCHIVO.TXT`, etc.

### Buscar solo archivos por extensión

```bash
find . -type f -name "*.log"
```

Busca archivos (no directorios) con extensión `.log`.

### Buscar solo directorios

```bash
find . -type d -name config
```

Busca directorios llamados `config`.

## Práctica sugerida

```bash
mkdir -p practica/directorio1 practica/directorio2
touch practica/directorio1/archivo1.txt
touch practica/directorio2/archivo2.log
```

Intenta luego ejecutar:

- `find practica`  
- `find practica -name "*.log"`  
- `find practica -name archivo1.txt`  
- `find practica -type d -name directorio2`

## Notas

- Usa `find` para búsquedas rápidas, sin depender de GUI.
- Es útil en scripts o tareas repetitivas de administración.

## 📚 Recursos adicionales

- 🎥 Video: [Aprende el comando find para buscar archivos en la terminal de Linux](https://youtu.be/TNT8Mcmta10)
- 💾 Repositorio GitHub: [aprendiz-linux/busqueda_linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/comandos_busqueda)
- 📺 Lista completa: [Reto 21 días comandos Linux](https://youtube.com/playlist?list=PLWa9LbkzT6D0DF_BKcZolZvvqY5FrxMba)

> ✍️ Estas notas acompañan un video corto para ayudar a nuevos usuarios de Linux a dominar la terminal con
> ejemplos simples y prácticos.
