# 🗑️ `rm` - Elimina archivos y directorios en Linux  

Bienvenido a **21 días de comandos Linux**, una serie para mejorar tu flujo en la terminal.  
Este documento complementa el video sobre el comando `rm` y te servirá como referencia rápida.  

## 🔍 ¿Qué es `rm`?  

El comando `rm` significa **"remove"** y se usa para **eliminar archivos y directorios** en la terminal de Linux.  

🚨 **⚠️ Precaución:** Los archivos eliminados con `rm` **no se pueden recuperar**. Úsalo con cuidado.  

## 📌 Uso básico  

Para eliminar un archivo, usa:  

```bash
rm archivo.txt
```

## ⚡ Opciones útiles  

| Comando | Descripción |
|---------|------------|
| `rm archivo` | Elimina un archivo. |
| `rm -i archivo` | Pregunta antes de eliminar un archivo. |
| `rm -r directorio` | Elimina un directorio y su contenido. |
| `rm -rf directorio` | Elimina un directorio sin pedir confirmación. **⚠️ Peligroso** |

### 📝 Ejemplos  

🔹 **Eliminar un archivo con confirmación:**  

```bash
rm -i importante.txt
```

🔹 **Eliminar un directorio con su contenido:**  

```bash
rm -r carpeta
```

🔹 **Eliminar un directorio sin confirmación (⚠️ Peligroso):**  

```bash
rm -rf datos/
```

## 🎯 Reto práctico  

1. Crea un archivo de prueba y elimínalo con `rm`.  
2. Usa `rm -i` para eliminar archivos con confirmación.  
3. Crea un directorio con archivos y bórralo con `rm -r`.  
4. Comenta en el video qué precauciones tomaste antes de usar `rm`.  

## 📢 Más recursos  

📖 **Documentación oficial:** [GNU Coreutils `rm`](https://www.gnu.org/software/coreutils/manual/html_node/rm-invocation.html)  

📺 **Video en YouTube:** [🔗 Día 5 - Aprende el comando rm y elimina archivos y directorios en Linux](https://youtu.be/Wjrs-7jY9gU)

🚀 **Sigue la serie en GitHub**: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

🔔 **Suscríbete para más contenido** y mejora tu dominio de la terminal Linux.
