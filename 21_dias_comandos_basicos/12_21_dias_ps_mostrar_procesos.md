# 🧠 ps - Muestra información de los procesos en Linux

## 🗒️ Descripción general

El comando `ps` (process status) se utiliza para mostrar información sobre los procesos que se están
ejecutando actualmente en el sistema. Por defecto, `ps` muestra solo los procesos asociados a la
terminal actual, pero puede utilizarse con diferentes opciones para obtener una vista más completa
del estado del sistema.

## 🧰 Comandos utilizados

### 📌 Ver los procesos actuales del usuario

```bash
ps
```

### 📌 Ver todos los procesos del sistema con detalles

```bash
ps aux
```

### 📌 Filtrar procesos por nombre utilizando `grep`

```bash
ps aux | grep bash
```

## 🧩 Explicación de opciones comunes en `ps aux`

* `a`: Muestra procesos de todos los usuarios.
* `u`: Muestra la información en formato de usuario (con columnas como USER, %CPU, %MEM, etc).
* `x`: Incluye procesos que no están asociados a una terminal.

## 🧵 Columnas comunes en `ps aux`

| Columna  | Significado                                      |
|----------|--------------------------------------------------|
| `USER`   | Usuario que ejecuta el proceso                   |
| `PID`    | ID del proceso (Process ID)                      |
| `%CPU`   | Porcentaje de uso de CPU                         |
| `%MEM`   | Porcentaje de uso de memoria                     |
| `VSZ`    | Tamaño virtual del proceso (en KB)               |
| `RSS`    | Tamaño real de memoria usada (en KB)             |
| `TTY`    | Terminal asociada al proceso                     |
| `STAT`   | Estado del proceso (ej. R = running, S = sleeping) |
| `START`  | Hora en que se inició el proceso                 |
| `TIME`   | Tiempo total de CPU utilizado                    |
| `COMMAND`| El comando que inició el proceso                 |

## 💡 Consejos prácticos

* Puedes buscar cualquier proceso con:

```bash
ps aux | grep <nombre_proceso>
```

* Para evitar que el propio `grep` aparezca en los resultados, puedes usar:

```bash
ps aux | grep '[f]irefox'
```

## 🔗 Recursos adicionales

* Documentación oficial del comando `ps`:
  [https://man7.org/linux/man-pages/man1/ps.1.html](https://man7.org/linux/man-pages/man1/ps.1.html)

## 📦 Repositorio del reto

Encuentra todos los comandos, scripts y notas del reto de 21 días en el repositorio de GitHub:

👉 [https://github.com/tuusuario/linux-21dias](https://github.com/tuusuario/linux-21dias)

Y no olvides visitar el canal de YouTube para ver el video práctico del día:

📺 [https://youtube.com/@TuCanalLinux](https://youtube.com/@TuCanalLinux)
