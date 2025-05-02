# 🏗️ `mkdir` - Crea directorios en la terminal de Linux  

Bienvenido a **21 días de comandos Linux**, una serie para mejorar tu flujo en la terminal.  
Este documento complementa el video sobre el comando `mkdir` y te servirá como referencia rápida.  

## 🔍 ¿Qué es `mkdir`?  

El comando `mkdir` significa **"make directory"** y se usa para **crear nuevos directorios** en la terminal de Linux.  

Si necesitas organizar tus archivos y proyectos, `mkdir` es un comando esencial.  

## 📌 Uso básico  

Para crear un nuevo directorio, usa:  

```bash
mkdir nombre_del_directorio
```

Ejemplo:  

```bash
mkdir proyectos
```

Esto crea un directorio llamado `proyectos` en tu ubicación actual.  

## ⚡ Opciones útiles  

| Comando  | Descripción |
|----------|------------|
| `mkdir nombre` | Crea un nuevo directorio. |
| `mkdir -p ruta/nombre` | Crea directorios anidados (si no existen). |
| `mkdir -v nombre` | Muestra un mensaje al crear el directorio. |

### 📝 Ejemplos  

🔹 **Crear un directorio simple:**  

```bash
mkdir documentos
```

🔹 **Crear una estructura de directorios anidados:**  

```bash
mkdir -p proyectos/codigo/src
```

🔹 **Mostrar un mensaje al crear un directorio:**  

```bash
mkdir -v mis_fotos
```

## 🎯 Reto práctico  

1. Crea un directorio llamado `prueba`.  
2. Dentro de `prueba`, crea tres directorios: `docs`, `scripts` y `configs`.  
3. Usa `mkdir -p` para crear la estructura `proyecto/src/bin` en un solo comando.  
4. Comenta en el video qué estructura creaste con `mkdir`.  

## 📢 Más recursos  

📖 **Documentación oficial:** [GNU Coreutils `mkdir`](https://www.gnu.org/software/coreutils/manual/html_node/mkdir-invocation.html) 

📺 **Video en YouTube:** [🔗 Día 4 - Aprende el comando mkdir para crear directorios en Linux](https://youtu.be/zs-KZazFa5o?si=TsT0GXtEwsEMs1RY)
 
🚀 **Sigue la serie en GitHub**: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

🔔 **Suscríbete para más contenido** y mejora tu dominio de la terminal Linux.
