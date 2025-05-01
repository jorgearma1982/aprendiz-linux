# 📡 ping: Prueba tu red en la terminal Linux

El comando `ping` es una herramienta de red que se utiliza para verificar la conectividad entre tu equipo y otro dispositivo en una red,
como un servidor, un router o una página web. Es una de las formas más sencillas y rápidas de diagnosticar problemas de red.

## 🧠 ¿Qué hace el comando `ping`?

Envía paquetes ICMP (Internet Control Message Protocol) al host de destino y espera una respuesta. Si el host responde, sabrás que está
activo y recibirás información sobre el tiempo de respuesta.

## 🛠️ Uso básico

```bash
ping <dirección IP o nombre de host>
```

Ejemplo:

```bash
ping google.com
```

Este comando enviará paquetes continuamente (hasta que lo detengas con `Ctrl + C`), mostrando los tiempos de respuesta.

## ✅ Opciones comunes

- `-c <número>`: Indica cuántos paquetes enviar (muy útil para pruebas específicas).
  
  ```bash
  ping -c 4 google.com
  ```

- `-i <segundos>`: Define el intervalo entre cada ping.

  ```bash
  ping -i 2 google.com
  ```

- `-t <TTL>`: Establece el "Time To Live" del paquete (cuántos saltos puede hacer).

  ```bash
  ping -t 64 google.com
  ```

> Nota: Algunas opciones pueden variar ligeramente dependiendo de la distribución de Linux.

## 📊 Cómo interpretar los resultados

Cada línea de salida muestra algo como:

```
64 bytes from 142.250.64.206: icmp_seq=1 ttl=115 time=15.3 ms
```

- `icmp_seq`: Número de secuencia del paquete enviado.
- `ttl`: Cuántos saltos pudo hacer el paquete antes de ser descartado.
- `time`: Tiempo en milisegundos que tardó en ir y volver.

Al final se resumen los paquetes enviados, recibidos, perdidos, y el tiempo promedio de respuesta.

## 🧪 Reto práctico

1. Verifica si tienes conexión a internet con:
   ```bash
   ping -c 4 google.com
   ```

2. Verifica la conectividad con tu router:
   ```bash
   ping -c 4 192.168.1.1
   ```

## Referencias

📌 Repositorio con todos los comandos y notas:  
[aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

🎥 Video en YouTube:  
[Día 17 - Aprende el comando ping para probar la red en Linux](https://www.youtube.com/watch?v=YCUPdlifiEM)
