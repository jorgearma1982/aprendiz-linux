# 🧠 Guía rápida: Instalación de Raspberry Pi OS en Raspberry Pi 3B+

Bienvenido/a a esta guía de referencia para complementar el video sobre cómo instalar **Raspberry Pi OS** en una
**Raspberry Pi 3B+**. Sigue estos pasos y tendrás tu sistema listo para comenzar tus proyectos Linux o IoT en minutos. 🛠️

## 📝 Requisitos

- Raspberry Pi 3B+ (o compatible)
- Tarjeta microSD de al menos 8 GB
- Lector de microSD
- Cable de alimentación compatible (5V/2.5A)
- Conexión a Internet
- Teclado, ratón y monitor HDMI (para la instalación inicial)

## 🌐 Paso 1: Descargar Raspberry Pi OS

1. Visita el sitio oficial:  
   [https://www.raspberrypi.com/software](https://www.raspberrypi.com/software)

2. Descarga e instala **Raspberry Pi Imager** para tu sistema operativo (Windows, macOS o Linux).

3. Abre Raspberry Pi Imager y selecciona:

   - Sistema operativo: Raspberry Pi OS (32-bit)  
   - Unidad de destino: tu microSD

## 💾 Paso 2: Crear microSD booteable

Usando **Raspberry Pi Imager**:

```bash
# En Raspberry Pi Imager:
# 1. Elige el sistema
# 2. Selecciona el destino (tu tarjeta SD)
# 3. Haz clic en "Escribir"
```

También puedes usar Balena Etcher:

```bash
# Alternativa:
# 1. Descarga Balena Etcher desde https://etcher.io
# 2. Selecciona la imagen de Raspberry Pi OS
# 3. Selecciona la microSD
# 4. Haz clic en Flash
```

## ⚡ Paso 3: Arranque inicial

1. Inserta la microSD en la Raspberry Pi.
2. Conecta el monitor, teclado y ratón.
3. Conecta la alimentación.

Verás la pantalla de arranque y el sistema operativo iniciará automáticamente.

## 🔧 Paso 4: Configuración inicial

En el primer arranque:

- Elige idioma y teclado
- Conéctate a WiFi o red por cable
- Actualiza el sistema si es necesario

Puedes abrir la terminal con:

```bash
Ctrl + Alt + T
```

Y actualizar manualmente con:

```bash
sudo apt update && sudo apt upgrade -y
```

## ✅ Verificación final

Para verificar que todo esté funcionando correctamente, abre una terminal y ejecuta:

```bash
uname -a
```

Esto mostrará información sobre el kernel y arquitectura.

## 🧪 Reto práctico

Conecta tu Raspberry Pi a internet y accede por SSH desde otra máquina (habilítalo desde la configuración):

```bash
ssh pi@<IP_de_tu_raspberry>
```

Usuario por defecto: `pi`  
Contraseña por defecto: `raspberry`

> ¡No olvides cambiar la contraseña por seguridad!

## ❤️ Enlaces útiles

- [Documentación oficial de Raspberry Pi OS](https://www.raspberrypi.com/documentation/)
- [Raspberry Pi Imager](https://www.raspberrypi.com/software/)
- [Comunidad de Raspberry Pi en Reddit](https://www.reddit.com/r/raspberry_pi/)

## 📚 Referencias

- 📁 Repositorio con comandos básicos de Linux: [aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)
- 🎥 Ve los videos de la serie de[21 díás comandos Linux básicos](https://youtu.be/VgPfK3PjBfo)

- 🎥 Video tutorial completo en YouTube:  
  [Como Instalar Raspberry Pi OS 12 en una Raspberry PI 3B+](https://youtu.be/WsR3w_IsaJc)

¿Te gustó esta guía? Visita el canal de YouTube para ver más contenido de Linux, automatización y proyectos prácticos. 🚀
