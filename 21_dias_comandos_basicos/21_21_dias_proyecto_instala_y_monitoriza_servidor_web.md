# 🖥️ Día 21 – Proyecto Final: Levantar un servidor web y monitorearlo con comandos Linux

## 📘 Descripción

¡Hola! Bienvenido y gracias por seguir conectado con este reto de 21 días de comandos Linux. Hoy cerramos con una práctica integradora: **levantar un servidor web básico con Python** y monitorear su comportamiento usando los comandos aprendidos.

**Lo que aprenderás hoy:**

- 📂 `mkdir`, `cd`, `ls` para organización
- 🔐 `chmod`, `chown`, `whoami` para permisos
- 🌐 `python3 -m http.server` para levantar servidor web
- 👁️ `ps`, `top`, `htop`, `netstat`, `curl`, `ping` para monitoreo
- 💥 `kill`, `pkill`, `rm` para detener y limpiar

🔧 **Reto práctico**: Levanta un servidor web local y usa los comandos aprendidos para ver qué ocurre en el sistema. ¡Explora los procesos, puertos, conexiones y mucho más!

## 💡 Comandos usados en este episodio

```bash
# Crear carpeta y archivo
mkdir -p ~/reto-dia21/web
cd ~/reto-dia21/web
echo "<h1>Servidor en funcionamiento</h1>" > index.html
ls -l

# Asignar permisos
whoami
chmod 644 index.html
chown $USER:$USER index.html

# Levantar servidor web
python3 -m http.server 8080

# Ver procesos y puertos abiertos
ps aux | grep python
top
htop
netstat -tulpn | grep 8080

# Hacer pruebas de conexión
curl http://localhost:8080
ping 127.0.0.1

# Detener proceso y limpiar
pkill -f "http.server"
rm -rf ~/reto-dia21
```

## 📦 Recursos adicionales

- Documentación de Python HTTP Server: https://docs.python.org/3/library/http.server.html
- Manual de `ps`: `man ps`
- Manual de `netstat`: `man netstat`

## 🎥 Referencias

Repositorio con ejemplos del reto:  
📁 [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

Video del día 21 en YouTube:  
▶️ **https://youtube.com/@linux-practico**
