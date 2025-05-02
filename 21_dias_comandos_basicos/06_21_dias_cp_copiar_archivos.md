# 📄 `cp` - Copia archivos y directorios en Linux  

Bienvenido a **21 días de comandos Linux**, una serie para mejorar tu flujo en la terminal.  
Este documento complementa el video sobre el comando `cp` y te servirá como referencia rápida.  

## 🔍 ¿Qué es `cp`?  

El comando `cp` significa **"copy"** y se usa para **copiar archivos y directorios** en la terminal de Linux.  

Si necesitas duplicar archivos o hacer respaldos, `cp` es tu herramienta ideal.  

## 📌 Uso básico  

Para copiar un archivo, usa:  

```bash
cp archivo.txt copia.txt
```

## ⚡ Opciones útiles  

| Comando | Descripción |
|---------|------------|
| `cp origen destino` | Copia un archivo a otro nombre o ubicación. |
| `cp -r directorio destino` | Copia un directorio completo. |
| `cp -i archivo destino` | Pregunta antes de sobrescribir. |
| `cp -u archivo destino` | Solo copia si el archivo de origen es más reciente. |

### 📝 Ejemplos  

🔹 **Copiar un archivo:**  

```bash
cp notas.txt respaldo.txt
```

🔹 **Copiar un directorio completo:**  

```bash
cp -r documentos respaldo
```

🔹 **Evitar sobrescribir archivos por error:**  

```bash
cp -i config.json /etc/
```

## 🎯 Reto práctico  

1. Copia un archivo a otro directorio.  
2. Usa `cp -r` para copiar un directorio completo.  
3. Prueba `cp -i` y observa qué sucede al sobrescribir un archivo.  
4. Comenta en el video qué opción te pareció más útil.  

## 📢 Más recursos  

📖 **Documentación oficial:** [GNU Coreutils `cp`](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html)  

📺 **Video en YouTube:** [🔗 Día 6 - Aprende el comando cp y copia archivos y directorios en Linux](https://youtu.be/f4hEumDfZdo)

🚀 **Sigue la serie en GitHub**: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

🔔 **Suscríbete para más contenido** y mejora tu dominio de la terminal Linux.
