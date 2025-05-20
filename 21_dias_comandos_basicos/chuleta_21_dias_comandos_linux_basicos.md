# 🐧 Cheatsheet: 21 comandos básicos para empezar en Linux

Una guía rápida para consultar los comandos básicos que aprendimos en los primeros 21 días del reto.
Ideal para principiantes que están comenzando en la administración de sistemas Linux. Cada comando está
clasificado y tiene un ejemplo práctico para recordar su uso.

## 📁 Gestión de archivos y directorios

| Comando | Descripción                      | Ejemplo rápido                             |
|---------|----------------------------------|--------------------------------------------|
| `ls`    | Lista archivos y directorios     | `ls -l`                                    |
| `pwd`   | Muestra la ruta actual           | `pwd`                                      |
| `cd`    | Cambia de directorio             | `cd /etc`                                  |
| `mkdir` | Crea un nuevo directorio         | `mkdir nueva_carpeta`                      |
| `rm`    | Elimina archivos o directorios   | `rm archivo.txt`                           |
| `cp`    | Copia archivos o directorios     | `cp archivo.txt copia.txt`                 |
| `mv`    | Mueve o renombra archivos        | `mv archivo.txt documentos/`               |

## 🔒 Permisos y usuarios

| Comando    | Descripción                          | Ejemplo rápido                            |
|------------|--------------------------------------|-------------------------------------------|
| `chmod`    | Cambia los permisos                  | `chmod +x script.sh`                      |
| `chown`    | Cambia el propietario                | `chown user:grupo archivo.txt`            |
| `whoami`   | Muestra el usuario actual            | `whoami`                                  |
| `sudo`     | Ejecuta comandos como superusuario   | `sudo apt update`                         |

## ⚙️ Procesos y recursos

| Comando  | Descripción                           | Ejemplo rápido                             |
|----------|---------------------------------------|--------------------------------------------|
| `ps`     | Muestra procesos en ejecución         | `ps aux`                                   |
| `top`    | Monitoriza procesos en tiempo real    | `top`                                      |
| `kill`   | Finaliza un proceso                   | `kill 1234`                                |

## 📦 Instalación y paquetes

| Comando  | Descripción                           | Ejemplo rápido                             |
|----------|---------------------------------------|--------------------------------------------|
| `apt`    | Gestiona paquetes (Debian/Ubuntu)     | `sudo apt install curl`                    |
| `dpkg`   | Administra paquetes locales `.deb`    | `sudo dpkg -i archivo.deb`                 |

## 🌐 Red y conectividad

| Comando     | Descripción                          | Ejemplo rápido                           |
|-------------|--------------------------------------|------------------------------------------|
| `ping`      | Verifica conectividad con un host    | `ping google.com`                        |
| `curl`      | Realiza peticiones HTTP              | `curl https://example.com`               |
| `netstat`   | Muestra puertos y conexiones         | `netstat -tuln`                          |
| `ifconfig`  | Muestra configuración de red         | `ifconfig`                               |

## 🚀 Aplicación práctica

| Comando                        | Descripción                         | Ejemplo rápido                             |
|-------------------------------|--------------------------------------|--------------------------------------------|
| `python3 -m http.server 8080` | Levanta un servidor web con Python   | `python3 -m http.server 8080`              |

---

**¿Dónde puedo encontrar más?**

📺 Mira los videos de cada comando en el [Reto 21 días comandos Linux](https://youtube.com/playlist?list=PLWa9LbkzT6D0DF_BKcZolZvvqY5FrxMba).

📘 Consulta el repositorio con todas las notas en GitHub: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)
