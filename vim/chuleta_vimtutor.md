# 📝 Chuleta de Comandos del Vimtutor

Repasa y práctica las lecciones del Vim con esta guía rápida del Vimtutor.

## 📘 Lección 1: Navegación Básica y Edición en Vim

| Comando/Tecla      | Ejemplo  | Descripción                                             |
|--------------------|----------|---------------------------------------------------------|
| `h`, `j`, `k`, `l` | `h`      | Mover el cursor a la izquierda, abajo, arriba, derecha. |
| `i`                | `iTexto` | Insertar texto antes del cursor.                        |
| `ESC`              |          | Salir del modo de inserción.                            |
| `:w`               |          | Guardar el archivo.                                     |
| `:q`               |          | Salir de Vim.                                           |
| `:wq`              |          | Guardar y salir.                                        |
| `ZZ`               |          | Guardar y salir (modo normal).                          |
| `:q!`              |          | Salir sin guardar.                                      |

## 🧹 Lección 2: Domina el Borrado y el Deshacer

| Comando/Tecla     | Ejemplo    | Descripción                                  |
|-------------------|------------|----------------------------------------------|
| `x`               | `x`        | Borrar el carácter bajo el cursor.           |
| `dw`              | `dw`       | Borrar una palabra.                          |
| `dd`              | `dd`       | Borrar una línea completa.                   |
| `u`               | `u`        | Deshacer la última acción.                   |
| `CTRL-R`          | `CTRL-R`   | Rehacer una acción deshecha.                 |

## ✍️ Lección 3: Pegar, Reemplazar y Cambiar Texto

| Comando/Tecla | Ejemplo   | Descripción                                      |
|---------------|-----------|--------------------------------------------------|
| `p`           | `p`       | Pegar después del cursor.                        |
| `P`           | `P`       | Pegar antes del cursor.                          |
| `r`           | `ra`      | Reemplazar un carácter por otro.                 |
| `R`           | `Rtexto`  | Reemplazo continuo de texto.                     |
| `cw`          | `cwTexto` | Cambiar una palabra.                             |
| `C`           | `CTexto`  | Cambiar desde el cursor hasta el final de línea. |

## 🔍 Lección 4: Buscar, Sustituir y Explorar el Archivo

| Comando/Tecla      | Ejemplo       | Descripción                                      |
|--------------------|---------------|--------------------------------------------------|
| `/texto`           | `/main`       | Buscar hacia adelante.                           |
| `?texto`           | `?main`       | Buscar hacia atrás.                              |
| `n` / `N`          | `n`           | Repetir búsqueda (mismo / opuesto dirección).    |
| `%`                | `%`           | Saltar entre paréntesis o llaves emparejadas.    |
| `:s/viejo/nuevo/`  | `:s/foo/bar/` | Sustituye el primer "foo" por "bar" en la línea. |
| `:s/viejo/nuevo/g` |               | Sustituye todas las ocurrencias en la línea.     |

## 💾 Lección 5: Comandos Externos y Escritura Selectiva

| Comando/Tecla   | Ejemplo        | Descripción                            |
|-----------------|----------------|----------------------------------------|
| `:!comando`     | `:!ls`         | Ejecutar un comando externo desde Vim. |
| `:w nombre.txt` | `:w copia.txt` | Guardar con otro nombre.               |
| `:r archivo`    | `:r notas.txt` | Insertar el contenido de otro archivo. |

## ⌨️  Lección 6: Insertar, Append y Configuración

| Comando/Tecla | Ejemplo       | Descripción                                                 |
|---------------|---------------|-------------------------------------------------------------|
| `o`           | `oTexto`      | Insertar una nueva línea debajo y entrar en modo inserción. |
| `O`           | `OTexto`      | Insertar una nueva línea encima.                            |
| `a`           | `aTexto`      | Insertar texto después del cursor.                          |
| `A`           | `ATexto`      | Insertar al final de la línea.                              |
| `:set option` | `:set number` | Establecer una opción de Vim.                               |
| `:set`        |               | Ver todas las opciones activas.                             |

## ❓ Lección 7: Ayuda en Vim y Despedida

| Comando/Tecla     | Ejemplo    | Descripción                                  |
|-------------------|------------|----------------------------------------------|
| `:help`           | `:help`    | Abre la ayuda de Vim.                        |
| `:help comando`   | `:help dd` | Ayuda sobre un comando específico.           |
| `:q`              |            | Cierra la ventana de ayuda.                  |

## ▶️  Mira la serie completa en YouTube

📺 Playlist completa de Vimtutor aquí: [Vimtutor](https://www.youtube.com/playlist?list=PLWa9LbkzT6D1P7aENxpyMKzEfkH0Qp7jZ)
