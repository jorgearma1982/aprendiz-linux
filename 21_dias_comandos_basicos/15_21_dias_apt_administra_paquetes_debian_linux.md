# 📦 apt - Administra paquetes en Debian Linux

Bienvenido a la guía de referencia del día 15 de la serie **"21 días de comandos Linux"**. Hoy aprenderás a utilizar el comando `apt`, una herramienta fundamental para instalar, actualizar y eliminar paquetes en sistemas basados en Debian como Ubuntu.

## 🧠 ¿Qué es `apt`?

`apt` es el **gestor de paquetes** predeterminado en sistemas basados en Debian. Permite instalar, actualizar y eliminar software directamente desde la terminal, accediendo a repositorios en línea con miles de paquetes disponibles.

## 🔄 Actualizar la lista de paquetes

Antes de instalar o actualizar, es recomendable actualizar la base de datos local de paquetes:

```bash
sudo apt update
```

Esto consulta los repositorios configurados en tu sistema y descarga información sobre las versiones más recientes de cada paquete.

## 📦 Instalar un paquete

Para instalar cualquier herramienta o programa:

```bash
sudo apt install <nombre-del-paquete>
```

Ejemplo:

```bash
sudo apt install htop
```

## 🧹 Eliminar un paquete

Para desinstalar un paquete que ya no necesitas:

```bash
sudo apt remove <nombre-del-paquete>
```

Ejemplo:

```bash
sudo apt remove htop
```

## ⬆️ Actualizar todos los paquetes

Para aplicar todas las actualizaciones pendientes del sistema:

```bash
sudo apt upgrade
```

## 🎯 Buenas prácticas

- Siempre ejecuta `sudo apt update` antes de instalar o actualizar paquetes.
- Usa `apt upgrade` regularmente para mantener tu sistema seguro y actualizado.
- Puedes combinar comandos, por ejemplo:

```bash
sudo apt update && sudo apt upgrade
```

## 🧪 Reto práctico

1. Instala un paquete divertido como `cowsay` o `figlet`.
2. Prueba cómo funciona:

    ```bash
    cowsay "¡Hola Linux!"
    figlet Linux
    ```

3. Luego, elimínalos con `sudo apt remove`.

## 📚 Recursos adicionales

- Documentación oficial de `apt`: https://manpages.debian.org/apt
- Lista de paquetes populares: https://packages.ubuntu.com/

- ▶️ Video de YouTube: 👉 Mira el video de este día para ver todos los ejemplos en acción: [Día 15 - Aprende el comando apt para Administrar Paquetes de software en Debian Linux](https://youtu.be/32BBwRmkIRU)

- 📁 Repositorio del curso: Accede a todos los ejemplos, notas y recursos desde nuestro repositorio en GitHub:  
🔗 [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)
