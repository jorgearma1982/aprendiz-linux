# 🛠️ sudo - Ejecuta comandos como administrador en Linux

## 📌 Descripción general

El comando `sudo` (super user do) permite a usuarios autorizados ejecutar comandos con privilegios de
administrador sin necesidad de cambiar de sesión o iniciar como el usuario `root`. Es una herramienta
esencial para tareas administrativas en sistemas Linux, ya que mejora la seguridad y el control de accesos.

## 🧠 ¿Por qué es importante?

* Evita iniciar sesión como root directamente, reduciendo riesgos.
* Permite delegar privilegios de manera segura y controlada.
* Registra todos los comandos ejecutados con `sudo` (útil para auditorías).

## 🧪 Ejemplos prácticos

### ✅ Ejecutar un comando con privilegios

```bash
sudo apt update
```

### ⚠️ Intentar sin `sudo`

```bash
apt update
```

*Error esperado:*  

`E: Could not open lock file /var/lib/apt/lists/lock - Permission denied`

## 🔐 ¿Qué pasa si no estás en el grupo sudo?

Si recibes este error:

```text
usuario no está en el archivo sudoers. Este incidente será reportado.
```

Significa que tu usuario no tiene privilegios para usar `sudo`. Un administrador puede agregarte con:

```bash
sudo usermod -aG sudo tu_usuario
```

## 🧼 Buenas prácticas

* Usa `sudo` solo cuando sea necesario.
* Evita hacer `sudo su` o entrar como root a menos que sea imprescindible.
* Finaliza la sesión de sudo con:

```bash
sudo -k
```

## Referencias

## 📚 Recursos adicionales

* `man sudo`
* ArchWiki: [Sudo](https://wiki.archlinux.org/title/Sudo)
* Guía de Ubuntu: [RootSudo](https://help.ubuntu.com/community/RootSudo)

Todo el contenido de esta serie está disponible en el repositorio:

👉 [🔗 aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

Y no olvides visitar el canal de YouTube para ver el video práctico del día:

📺 [Día 11 - Aprende el comando sudo para ejecutar comandos como administrador en Linux](https://youtu.be/bS7JElA2GI4)
