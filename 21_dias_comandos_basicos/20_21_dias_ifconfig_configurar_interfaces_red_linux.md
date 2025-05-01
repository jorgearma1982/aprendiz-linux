# 🧠 ifconfig - Configura interfaces de red en Linux

`ifconfig` es una herramienta clásica de Linux que permite ver y configurar las interfaces de red del sistema. Aunque ha
sido reemplazada por `ip` en muchas distribuciones modernas, sigue siendo útil, sobre todo en entornos minimalistas o en
versiones anteriores de Linux.

## ✅ ¿Para qué sirve `ifconfig`?

- Ver las interfaces de red activas
- Ver todas las interfaces, incluidas las inactivas
- Consultar direcciones IP asignadas
- Activar o desactivar interfaces manualmente
- Diagnosticar problemas básicos de red

## 🧪 Uso básico

```bash
ifconfig
```

Este comando muestra las interfaces activas, su dirección IP, máscara de red, paquetes enviados y recibidos, entre otros datos.

## 📋 Ver todas las interfaces (incluso las inactivas)

```bash
ifconfig -a
```

Muestra todas las interfaces, estén activas o no.

## 🔍 Ver detalles de una interfaz específica

```bash
ifconfig eth0
```

Reemplaza `eth0` por el nombre de la interfaz que quieras inspeccionar.

## 🔧 Activar o desactivar una interfaz (requiere privilegios)

```bash
sudo ifconfig eth0 down
sudo ifconfig eth0 up
```

Estos comandos permiten deshabilitar o habilitar una interfaz de red. Útil en pruebas de conectividad o scripts.

## 🛠️ Instalación (si no está disponible)

En algunas distribuciones modernas `ifconfig` no está instalado por defecto. Puedes instalarlo con:

```bash
sudo apt update
sudo apt install net-tools
```

## 🚀 Prueba práctica

1. Abre una terminal y ejecuta `ifconfig` para ver tu IP actual.
2. Luego prueba `ifconfig -a` para ver todas las interfaces.
3. Finalmente, localiza tu interfaz principal (`eth0`, `wlan0`, etc.) y revisa su configuración con `ifconfig <nombre_de_interfaz>`.

## 📚 Recursos adicionales

- Documentación oficial de net-tools: https://man7.org/linux/man-pages/man8/ifconfig.8.html
- Alternativa moderna: el comando `ip` (lo veremos mañana)

Encuentra todos los comandos y ejercicios en el repositorio del reto:  
🔗 [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

Mira el video de este día en YouTube:  
▶️ https://youtube.com/tu-video-dia20
