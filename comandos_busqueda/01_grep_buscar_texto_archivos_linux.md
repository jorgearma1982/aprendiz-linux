# 🔍 `grep` - Aprende a buscar texto dentro de archivos en la terminal Linux

📅 **Serie Especial: Comandos de búsqueda en Linux**  
🎯 **Objetivo**: Desarrollar fluidez en la terminal para buscar información dentro de archivos y directorios
sin necesidad de herramientas externas.

## 🔍 ¿Qué es `grep`?

El comando `grep` permite buscar líneas que contienen un texto específico dentro de uno o varios archivos. Es
ideal para leer archivos de texto, logs del sistema o configuraciones.

> 🧠 Significado del nombre: **G**lobal **R**egular **E**xpression **P**rint

## 🛠️ Uso básico

```bash
grep texto archivo.txt
```

Busca todas las líneas que contengan `"texto"` dentro de `archivo.txt`.

## 🧩 Opciones comunes

| Opción         | Descripción                          |
|----------------|--------------------------------------|
| `-i`           | Ignora mayúsculas/minúsculas         |
| `-n`           | Muestra el número de línea           |
| `--color=auto` | Resalta el texto encontrado en color |

**Ejemplo:**

```bash
grep -in --color=auto error archivo.log
```

## 📁 Buscar en varios archivos

```bash
grep usuario *.conf
```

Busca la palabra `usuario` en todos los archivos con extensión `.conf` en el directorio actual.

## 🔁 Búsqueda recursiva en carpetas

```bash
grep -r clave ./documentos
```

Busca `"clave"` en todos los archivos dentro del directorio `documentos` y sus subdirectorios.

## 🧪 Reto para practicar

Crea una carpeta de prueba:

```bash
mkdir prueba-grep
cd prueba-grep
```

Crea algunos archivos:

```bash
echo "Este es un texto de ejemplo" > archivo1.txt
echo "Otro archivo con texto similar" > archivo2.txt
echo "ERROR: algo falló" > errores.log
```

Prueba estas búsquedas:

```bash
grep texto archivo1.txt
grep -i error errores.log
grep -r texto .
```

## 📚 Recursos adicionales

- 🎥 Video: [grep - Aprende a buscar texto dentro de archivos en la terminal Linux](https://youtu.be/a62kLa-ptnc)
- 💾 Repositorio GitHub: [aprendiz-linux/busqueda_linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/comandos_busqueda)
- 📺 Lista completa: [Reto 21 días comandos Linux](https://youtube.com/playlist?list=PLWa9LbkzT6D0DF_BKcZolZvvqY5FrxMba)

> ✍️ Estas notas acompañan un video corto para ayudar a nuevos usuarios de Linux a dominar la terminal con
> ejemplos simples y prácticos.
