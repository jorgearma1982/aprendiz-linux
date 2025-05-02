# 📍 `pwd` - Muestra el directorio de trabajo actual en Linux  

Bienvenido a **21 días de comandos Linux**, una serie para mejorar tu flujo en la terminal.  
Este documento complementa el video sobre el comando `pwd` y te servirá como referencia rápida.  

## 🔍 ¿Qué es `pwd`?  

El comando `pwd` significa **"print working directory"** y se usa para **mostrar la ruta absoluta** del directorio en
el que te encuentras actualmente en la terminal.  

Siempre que estés trabajando en la terminal, `pwd` te ayudará a saber en qué parte del sistema de archivos te encuentras.  

## 📌 Uso básico  

Para mostrar la ruta del directorio actual, simplemente ejecuta:  

```bash
pwd
```

Ejemplo de salida:  

```bash
/home/usuario
```

Esto indica que estás en el directorio `/home/usuario`.  

## ⚡ Opciones útiles  

| Opción  | Descripción |
|---------|------------|
| `pwd`   | Muestra la ruta completa del directorio actual. |
| `pwd -L` | Muestra la ruta lógica (puede incluir enlaces simbólicos). |
| `pwd -P` | Muestra la ruta física real (resuelve enlaces simbólicos). |

### 📝 Ejemplos  

🔹 **Mostrar la ruta actual:**  

```bash
pwd
```

🔹 **Mostrar la ruta lógica (con enlaces simbólicos):**  

```bash
pwd -L
```

🔹 **Mostrar la ruta física (resolviendo enlaces simbólicos):**  

```bash
pwd -P
```

## 🎯 Reto práctico  

1. Abre la terminal y ejecuta `pwd` en diferentes ubicaciones.  
2. Usa `cd` para moverte a otro directorio y vuelve a ejecutar `pwd`.  
3. Si usas enlaces simbólicos, prueba `pwd -P` y `pwd -L` para ver la diferencia.  
4. Comenta en el video qué aprendiste y cómo usas `pwd` en tu día a día.  

## 📢 Más recursos  

📖 **Documentación oficial:** [GNU Coreutils `pwd`](https://www.gnu.org/software/coreutils/manual/html_node/pwd-invocation.html)

📺 **Video en YouTube:** [🔗 Día 2 - Aprende pwd y descubre en que directorio estas en Linux](https://youtu.be/r8oF7tlP0KE?si=uvHNk7Ggx98hDdX6)

🚀 **Sigue la serie en GitHub**: [🔗 aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

🔔 **Suscríbete para más contenido** y mejora tu dominio de la terminal Linux.
