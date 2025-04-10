# 🔐 chmod - Controla permisos de archivos en Linux

## 📌 Resumen

El comando `chmod` permite cambiar los permisos de archivos y directorios en Linux. Existen dos formas
principales de modificar los permisos:

1. **Notación simbólica:** Usando `r` (lectura), `w` (escritura), `x` (ejecución).
2. **Notación numérica:** Asignando valores (`4` para lectura, `2` para escritura, `1` para ejecución).

## 📚 Comandos clave

### 🔹 Ver permisos de un archivo

```bash
ls -l archivo.txt
```

### 🔹 Cambiar permisos con notación simbólica

```bash
chmod u+x script.sh   # Agregar permiso de ejecución al usuario
chmod o-w archivo.txt # Quitar permiso de escritura a otros
```

### 🔹 Cambiar permisos con notación numérica

```bash
chmod 755 mi_programa  # Permisos: rwxr-xr-x
chmod 600 archivo.txt  # Permisos: rw-------
```

### ⚠️ No recomendado

```bash
chmod 777 archivo_secreto.txt  # Todos pueden leer, escribir y ejecutar (inseguro)
```

### ✅ Mejor alternativa

```bash
chmod 600 archivo_secreto.txt  # Solo el dueño puede leer y escribir
```

## 🎯 Reto práctico

Modifica los permisos de un archivo para que solo su dueño pueda leerlo y escribir en él, pero nadie más pueda acceder.  
Sugerencia: Usa `chmod 600 archivo.txt`.  

📺 **Video en YouTube:** _[https://www.youtube.com/watch?v=OjTPn34Ms1Q]_
