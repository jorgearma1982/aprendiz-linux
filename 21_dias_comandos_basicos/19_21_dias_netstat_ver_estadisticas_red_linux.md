# 📌 netstat - Ve estadisticas de red en Linux

## 📚 Descripción general

`netstat` es una herramienta de red que permite a los administradores de sistemas inspeccionar conexiones activas, puertos en escucha,
interfaces de red y estadísticas de protocolo. Aunque en sistemas más recientes ha sido reemplazada por `ss`, sigue siendo ampliamente
utilizada y comprendida.

## 🧠 Conceptos clave

- **Conexiones activas:** Permite ver qué direcciones IP están conectadas al sistema y en qué puertos.
- **Puertos en escucha:** Muestra qué servicios están esperando conexiones entrantes.
- **Protocolo:** TCP o UDP, clave para interpretar el tráfico.
- **PID/Program name:** Puedes ver qué programa está detrás de cada puerto (requiere permisos de administrador).
- **Opciones útiles:**
  - `-t` → TCP
  - `-u` → UDP
  - `-n` → Mostrar direcciones numéricas (sin resolución DNS)
  - `-p` → Mostrar el proceso y PID
  - `-l` → Solo mostrar sockets en escucha

## 🧪 Ejemplos prácticos

-  Ver todas las conexiones

```bash
netstat
```

-  Ver conexiones activas TCP/UDP sin resolver nombres

```bash
netstat -tun
```

- Ver puertos en escucha con procesos (requiere sudo)

```bash
sudo netstat -tulpn
```

- Ver estadísticas de red (por protocolo)

```bash
netstat -s
```

## ✅ Buenas prácticas

- Usar `sudo` para obtener la información completa de procesos con `-p`.
- Combinar flags como `-tulpn` para obtener vistas completas de conexiones de red y procesos.
- Complementar con herramientas modernas como `ss` o `lsof` para entornos actuales.

## 🧩 Reto práctico

1. Ejecuta `sudo netstat -tulpn` en tu máquina.
2. Identifica qué servicios están escuchando y en qué puertos.
3. Verifica si hay conexiones establecidas que no esperabas.
4. Comparte en tu bitácora o espacio de práctica qué descubriste sobre tu sistema.

## 🔗 Recursos adicionales

- [Documentación oficial GNU/Linux de net-tools](https://linux.die.net/man/8/netstat)
- [Alternativa moderna: comando `ss`](https://man7.org/linux/man-pages/man8/ss.8.html)


Encuentra todos los scripts y materiales del reto en:  
📁 GitHub: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

🎥 Video en YouTube: disponible a partir del día 19 en la [lista de reproducción oficial](https://www.youtube.com/playlist?list=PL-RETO-LINUX21)
