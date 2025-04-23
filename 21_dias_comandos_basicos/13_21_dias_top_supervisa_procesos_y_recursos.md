# 🐧 top - Supervisa procesos y recursos en Linux

## 🧠 Resumen

El comando `top` permite monitorear en tiempo real el uso de recursos del sistema y los procesos en ejecución. Es ideal para detectar procesos que consumen mucha CPU o memoria, y para tener una visión general de la carga del sistema.

### 📚 Conceptos clave

* `top`: Muestra procesos activos, uso de CPU, memoria y otros datos del sistema en tiempo real.
* `PID`: ID del proceso.
* `%CPU` / `%MEM`: Porcentaje de uso de CPU y memoria por cada proceso.
* `COMMAND`: El comando que inició el proceso.

## ⚙️ Opciones útiles

* `P`: Ordena procesos por uso de CPU.
* `M`: Ordena procesos por uso de memoria.
* `k`: Mata un proceso (requiere ingresar el PID).
* `/`: Permite buscar procesos por nombre.
* `q`: Salir de la interfaz interactiva de `top`.

## 💡 Tips prácticos

* Usa `top` para detectar cuellos de botella en tu sistema.
* Puedes ejecutar `top -d 1` para actualizar cada segundo.
* Para obtener una versión más amigable visualmente, prueba el comando `htop` (requiere instalación adicional).

## 🧪 Reto práctico

Abre una terminal y ejecuta:

```bash
top
```

* Encuentra el proceso que más CPU está usando.
* Filtra por nombre un proceso que reconozcas con `/`.
* Sal con la tecla `q`.

## 📎 Referencias

* Documentación oficial de GNU `top`:  
  https://man7.org/linux/man-pages/man1/top.1.html

* Video del día en YouTube:  
  [🔗 Enlace al video](https://www.youtube.com/watch?v=-xTE-rqFwuM)

* Repositorio con ejemplos y notas del reto:  
  [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)
