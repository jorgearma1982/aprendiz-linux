# 📘 curl - Accede a contenidos web desde la terminal Linux

## 🧠 Comando del día: `curl`

`curl` es una herramienta de línea de comandos que te permite transferir datos desde o hacia un servidor remoto. Es especialmente útil para realizar
peticiones HTTP, descargar archivos o interactuar con APIs REST.

## 📌 Uso básico

### Ver el contenido de una página web:

```bash
curl https://example.com
```

Este comando descarga y muestra el HTML de la página en la terminal.

## Obtener solo los encabezados HTTP

```bash
curl -I https://example.com
```

Esto solicita únicamente los encabezados, sin descargar el cuerpo de la respuesta. Útil para diagnosticar servidores o verificar redirecciones.

## Descargar un archivo y guardar con su nombre original

```bash
curl -O https://example.com/archivo.txt
```

Guarda el archivo con el mismo nombre que tiene en el servidor.

## 🧪 Práctica recomendada

1. Usa `curl` para ver el HTML de tu sitio favorito.
2. Usa `-I` para ver los encabezados de una URL.
3. Descarga un archivo público usando `-O`.

## 📚 Recursos adicionales

- Manual oficial: `man curl`
- Documentación: https://curl.se/docs/

## 📺 Video del día

Mira el video con la explicación práctica de este comando en YouTube:  
[👉 Día 18 - Aprende el comando curl para hacer descargas Web en Linux](https://www.youtube.com/watch?v=daINQRhk_Bw)

## 📦 Repositorio del reto

Todo el contenido del reto "Linux en 21 días" está disponible en el siguiente repositorio:  
[https://github.com/tuusuario/linux-en-21-dias](https://github.com/tuusuario/linux-en-21-dias)
