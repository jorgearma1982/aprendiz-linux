# 🧨 kill - Termina procesos en Linux

Hoy aprenderás a usar el comando `kill`, una herramienta poderosa para terminar procesos en Linux cuando se quedan colgados o consumen muchos recursos. Vamos a ver cómo identificar procesos, cómo usar señales y cuál es la diferencia entre terminarlos de forma suave o forzada.

## 📌 ¿Qué hace el comando `kill`?

El comando `kill` envía señales a los procesos usando su **PID (Process ID)**. La señal por defecto es `SIGTERM` (terminación ordenada), pero también puedes usar señales más agresivas como `SIGKILL` si un proceso no responde.

## 🧠 Conceptos clave

* **PID**: Identificador único de un proceso en ejecución.
* **Señales**: Instrucciones que se envían a los procesos. Algunas comunes:
  * `SIGTERM` (15): Termina el proceso de forma normal.
  * `SIGKILL` (9): Forza la terminación inmediata.
* Puedes listar todas las señales disponibles con:

```bash
kill -l
```

## 🔍 Cómo encontrar el PID de un proceso

Usa `ps` y `grep` para buscar procesos por nombre:

```bash
ps aux | grep firefox
```

Esto mostrará una línea con el nombre del proceso, incluyendo su PID.

## 💥 Cómo usar `kill`

Con el PID en mano, puedes enviar una señal al proceso:

```bash
kill 1234        # Termina con SIGTERM
kill -9 1234     # Termina forzadamente con SIGKILL
```

## 🧪 Ejemplo práctico

1. Ejecuta un proceso "lento" en segundo plano:

```bash
sleep 1000 &
```

2. Encuentra su PID:

```bash
ps aux | grep sleep
```

3. Termínalo con `kill`:

```bash
kill <PID>
```

## 🚀 Buenas prácticas

* Usa primero `kill` sin `-9` para permitir al proceso cerrar correctamente.
* Usa `kill -9` solo si el proceso no responde.
* ¡Evita terminar procesos críticos del sistema!

## Referencias

📦 Repositorio con ejemplos: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

🎥 Video de este día en YouTube: [Día 14 - Aprende el comando kill para terminar procesos en Linux](https://www.youtube.com/watch?v=-8c3-6OANek&t=1s)
