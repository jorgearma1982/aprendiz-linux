# 🛠️ whoami - Identifica usuarios en Linux

## 🎯 Objetivo  

Hoy aprenderás a utilizar el comando `whoami` para identificar con qué usuario estás operando en el sistema.  

## 📌 Descripción  

El comando `whoami` muestra el nombre del usuario actual que está ejecutando la terminal. Es útil para verificar
con qué permisos estás trabajando, especialmente en entornos multiusuario.  

## 🚀 Uso básico  

Para saber qué usuario está ejecutando la terminal, simplemente escribe:  

```bash
whoami
```

Este comando mostrará el nombre del usuario que ha iniciado sesión.  

### 🔍 Diferencia entre `whoami` e `id`  

- `whoami`: Solo muestra el nombre del usuario activo.  
- `id`: Proporciona información detallada, como UID, GID y grupos a los que pertenece el usuario.  

Ejemplo de uso:  

```bash
id
```

Salida típica de `id`:  

```bash
uid=1000(usuario) gid=1000(usuario) grupos=1000(usuario),27(sudo)
```

## 🔄 Verificando usuario tras cambiar de sesión  

Si cambias a otro usuario con `su` o `sudo -i`, puedes verificarlo con `whoami`:  

```bash
sudo -i
whoami
```

Si cambiaste correctamente a root, el comando mostrará:  

```bash
root
```

## 🏆 Reto práctico  

1️⃣ Ejecuta `whoami` en tu terminal.  
2️⃣ Usa `sudo -i` o `su - otro_usuario` y vuelve a ejecutar `whoami`.  
3️⃣ Comparte en los comentarios si alguna vez has ejecutado un comando con el usuario equivocado.  

## Referencias

Todo el contenido de esta serie está disponible en el repositorio:

👉 [🔗 aprendiz-linux](https://github.com/jorgearma1982/aprendiz-linux/tree/main/21_dias_comandos_basicos)

📺 **Mira el video en YouTube:** [🔗 Día 10 - Aprende el comando whoami para identificar usuarios en Linux](https://youtu.be/55-csIxAueI)
