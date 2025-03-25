# 🔀 `mv` - Mueve y renombra archivos en Linux  

Bienvenido a **21 días de comandos Linux**, una serie para mejorar tu flujo en la terminal.  
Este documento complementa el video sobre el comando `mv` y te servirá como referencia rápida.  

---

## 🔍 ¿Qué es `mv`?  

El comando `mv` significa **"move"** y se usa para **mover o renombrar archivos y directorios** en Linux.  

---

## 📌 Uso básico  

Para mover un archivo a otra ubicación, usa:  

```bash
mv archivo.txt Documentos/
```

Para renombrar un archivo, usa:  

```bash
mv viejo.txt nuevo.txt
```

---

## ⚡ Opciones útiles  

| Comando | Descripción |
|---------|------------|
| `mv origen destino` | Mueve o renombra un archivo. |
| `mv -i archivo destino` | Pregunta antes de sobrescribir. |
| `mv -u archivo destino` | Solo mueve si el archivo de origen es más reciente. |

### 📝 Ejemplos  

🔹 **Mover un archivo a otro directorio:**  
```bash
mv foto.jpg Imágenes/
```

🔹 **Renombrar un archivo:**  
```bash
mv notas.txt notas_viejas.txt
```

🔹 **Evitar sobrescribir archivos por error:**  
```bash
mv -i reporte.pdf Documentos/
```

---

## 🎯 Reto práctico  

1. Mueve un archivo a otro directorio y confirma con `ls`.  
2. Usa `mv` para renombrar un archivo.  
3. Prueba `mv -i` y observa qué sucede al sobrescribir un archivo.  
4. Comenta en el video cómo usas `mv` en tu día a día.  

---

## 📢 Más recursos  

📺 **Video en YouTube:** [🔗 Ver Video](#) *(enlace cuando esté disponible)*  
📖 **Documentación oficial:** [GNU Coreutils `mv`](https://www.gnu.org/software/coreutils/manual/html_node/mv-invocation.html)  

---

🚀 **Sigue la serie en GitHub**: [🔗 Repositorio](#) *(enlace cuando esté disponible)*  
🔔 **Suscríbete para más contenido** y mejora tu dominio de la terminal Linux.  
