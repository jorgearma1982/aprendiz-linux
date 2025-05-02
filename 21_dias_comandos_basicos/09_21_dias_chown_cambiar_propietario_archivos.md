# 🧑 chown - Cambia propietarios de archivos en Linux

**21 días de comandos Linux** — Mejora tu flujo en la terminal 🧠💻

## 🎯 ¿Qué hace el comando `chown`?

El comando `chown` (change owner) permite cambiar el **propietario** y/o el **grupo** de uno o más archivos
o directorios. Es útil para administrar permisos de acceso y organizar los recursos entre usuarios del sistema.

## 🧠 Conceptos clave

* Todo archivo o directorio en Linux tiene un **usuario propietario** y un **grupo propietario**.
* Cambiar el propietario puede afectar el acceso de otros usuarios al archivo.
* Solo el usuario root (o con privilegios sudo) puede cambiar propietarios.

## 🧪 Ejemplos prácticos

```bash
# Cambiar el propietario de un archivo
sudo chown juan archivo.txt

# Cambiar el propietario y el grupo
sudo chown juan:devs proyecto/

# Cambiar propietario de forma recursiva
sudo chown -R juan:juan /var/www/html
```

## 🛡️ Seguridad y buenas prácticas

* Ten cuidado al usar `-R` (recursivo), especialmente en directorios del sistema.
* Verifica los permisos antes y después del cambio con `ls -l`.
* Usa este comando solo cuando sea necesario; cambiar dueños incorrectamente puede romper servicios.

## 🧩 Reto práctico

Crea un archivo de prueba:

```bash
touch prueba.txt
```

Cámbiale el propietario a tu usuario (si no lo eres ya):

```bash
sudo chown $USER prueba.txt
```

Verifica con:

```bash
ls -l prueba.txt
```

(Opcional) Crea un grupo y cambia el grupo propietario:

```bash
sudo groupadd equipo
sudo chown $USER:equipo prueba.txt
```

## Referencias

📺 Mira el video explicativo en YouTube:  
👉 [Dia 9 - Aprende el comando chown para cambiar propietarios de archivos en Linux](https://youtu.be/DMfBP8worhI)

Todo el contenido de esta serie está disponible en el repositorio:

👉 [🔗 aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

¡Nos vemos en el próximo día con más comandos esenciales de Linux! 🚀🐧
