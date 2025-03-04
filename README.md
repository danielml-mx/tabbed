# tabbed - añade pestañas a tus programas

Esta es mi versión personal de [suckless
tabbed](https://tools.suckless.org/tabbed/), la cual utilizo
exclusivamente con [st](https://st.suckless.org/). Me ha
servido para mi workflow pues me permite hacer varias tareas
en diferentes sesiones de la terminal optimizando el uso del
espacio en pantalla.

![screenshot-030325-231147](https://github.com/user-attachments/assets/09046b72-8d1a-4c28-aa10-b6bda6665f40)

Esta versión está configurada para tener los keybindings de
un navegador web, y además incluye las siguientes funciones
añadidas principalmente a través de parches: 

- Configuración estética a través de Xresources
- Numeración para cada pestaña
- Soporte de transparencia del cliente hecho pestaña
  (requiere de un compositor)
- Soporte para el ícono del cliente

Una lista de las funcionalidades más importantes y sus
correspondientes combinaciones de teclas puede ser
consultada debajo. Aunque me parece que tienen
predeterminados bastante sensibles, todas pueden ser
modificadas editando `config.h`.

## Keybindings
| Teclas | Descripción |
|--|--|
|`Ctrl + T`  |Nueva pestaña|
|`Ctrl + Shift + T`  |Nueva pestaña en el directorio de la actual pestaña|
|`Ctrl + W`  |Cerrar pestaña|
|`Ctrl + Tab`|Siguiente pestaña|
|`Ctrl + Shift + Tab`|Anterior pestaña|
|`Ctrl + [1..9]`|Ver la pestaña [1..9]|
|`Ctrl + Shift + H`|Mover la actual pestaña hacia la izquierda|
|`Ctrl + Shift + L`|Mover la actual pestaña hacia la derecha|

