# 📦 dpkg - Administra paquetes `.deb` en Linux

## 🤓 ¿Qué es `dpkg`?

`dpkg` es la herramienta base para la gestión de paquetes `.deb` en sistemas basados en Debian, como Ubuntu. A diferencia de `apt`, que resuelve dependencias automáticamente, `dpkg` trabaja de forma más directa, permitiendo instalar, listar o eliminar paquetes de manera manual.

Es ideal cuando tienes un paquete `.deb` que descargaste tú mismo y quieres instalarlo sin pasar por repositorios.

## 📥 Instalar un paquete `.deb`

```bash
sudo dpkg -i nombre-del-paquete.deb
```

> Instala el paquete especificado. Si faltan dependencias, puedes resolverlas luego con `sudo apt install -f`.

## 📋 Listar paquetes instalados

```bash
dpkg -l
```

> Muestra una lista de todos los paquetes instalados en el sistema.

## 🔍 Ver detalles de un paquete instalado

```bash
dpkg -s nombre-del-paquete
```

> Muestra información del paquete: versión, estado, dependencias, descripción, etc.

## 🧾 Ver archivos instalados por un paquete

```bash
dpkg -L nombre-del-paquete
```

> Lista todos los archivos que se instalaron como parte de ese paquete.

## ❌ Eliminar un paquete

```bash
sudo dpkg -r nombre-del-paquete
```

> Elimina el paquete, pero puede dejar archivos de configuración.

## ✅ Tip adicional

Si durante la instalación de un `.deb` aparecen errores de dependencias, puedes solucionarlos con:

```bash
sudo apt install -f
```

Esto forzará la instalación de las dependencias faltantes.

## 📚 Más información

- Documentación oficial: https://man7.org/linux/man-pages/man1/dpkg.1.html

## 📺 Recurso adicional

Este contenido forma parte de la serie **"21 días, 21 comandos de Linux"** disponible en nuestro canal de YouTube.

🔗 Video del día: [Día 16 - Aprende el comando dpkg para gestionar paquetes .deb en Linux](https://youtu.be/-ZLZiPlfmd4)  
📦 Repositorio con todos los ejemplos: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)
