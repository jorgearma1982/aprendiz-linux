# 📂 `ls` - Lista archivos y directorios en Linux  

Bienvenido a **21 días de comandos Linux**, una serie para mejorar tu flujo en la terminal.  
Este documento complementa el video sobre el comando `ls` y te servirá como referencia rápida.  

## 🔍 ¿Qué es `ls`?  

El comando `ls` se usa para **listar archivos y directorios** en la terminal de Linux.  
Es una alternativa al explorador de archivos gráfico, pero mucho más poderosa.  

## 📌 Uso básico  

Lista los archivos y directorios en la ubicación actual:  

```bash
ls
```

Ejemplo de salida:  

```bash
Documentos  Descargas  Imágenes  Música  Escritorio
```

## ⚡ Opciones útiles  

| Opción  | Descripción |
|---------|------------|
| `ls -l` | Muestra detalles como permisos, tamaño y fecha de modificación. |
| `ls -a` | Muestra archivos ocultos (los que empiezan con `.`). |
| `ls -lh` | Muestra los tamaños de archivos en un formato legible (KB, MB, GB). |
| `ls -lt` | Ordena por fecha de modificación, de más reciente a más antiguo. |
| `ls -lhS` | Ordena por tamaño del archivo, de mayor a menor. |

### 📝 Ejemplos  

🔹 **Lista en formato detallado:**  

```bash
ls -l
```

🔹 **Lista incluyendo archivos ocultos:**  

```bash
ls -a
```

🔹 **Lista con tamaños legibles:**  

```bash
ls -lh
```

🔹 **Ordena por fecha de modificación:**  

```bash
ls -lt
```

## 🎯 Reto práctico  

1. Abre la terminal y ejecuta `ls` en tu directorio personal.  
2. Usa `ls -l` y compara los permisos y tamaños de los archivos.  
3. Prueba `ls -a` para ver los archivos ocultos.  
4. Comenta en el video qué opción te pareció más útil.  

## 📢 Más recursos  

📺 **Video en YouTube:** [🔗 Ver Video](https://youtu.be/1uZL1TXXxqo)
📖 **Documentación oficial:** [GNU Coreutils `ls`](https://www.gnu.org/software/coreutils/manual/html_node/ls-invocation.html)  

🚀 **Sigue la serie en GitHub**: [🔗 Repositorio](https://github.com/jorgearma1982/aprendiz-linux)
🔔 **Suscríbete para más contenido** y mejora tu dominio de la terminal Linux.
