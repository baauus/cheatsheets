# LazyVim

**Nota:** `<leader>` por defecto es la **barra espaciadora** (Space)

---

## 🔍 Navegación y Búsqueda (Telescope)

```bash
`<leader>ff`          # Buscar archivos (find files)
`<leader>fg`          # Buscar por contenido en archivos (grep)
`<leader>fb`          # Buscar en buffers abiertos
`<leader>fr`          # Archivos recientes
`<leader>fw`          # Buscar palabra bajo el cursor
`<leader>/`           # Buscar en buffer actual
`<leader>:`           # Historial de comandos
```
---

## 📁 Explorador de Archivos (Neo-tree)

```bash
`<leader>e`           # Toggle Neo-tree
`<leader>E`           # Neo-tree enfocado en archivo actual
```
### Dentro de Neo-tree:

```bash
`a`                   # Crear archivo
`A`                   # Crear carpeta
`d`                   # Eliminar
`r`                   # Renombrar
`x`                   # Cortar
`c`                   # Copiar
`p`                   # Pegar
`y`                   # Copiar ruta del archivo
`h`                   # Cerrar carpeta / subir nivel
`l` o `Enter`         # Abrir carpeta/archivo
`q`                   # Cerrar Neo-tree
```

---

## 📝 Edición Básica

```bash
`i`                   # Modo inserción (antes del cursor)
`a`                   # Modo inserción (después del cursor)
`o`                   # Nueva línea abajo y modo inserción
`O`                   # Nueva línea arriba y modo inserción
`Esc`                 # Volver a modo normal
`u`                   # Deshacer
`Ctrl+r`              # Rehacer
`dd`                  # Borrar línea
`yy`                  # Copiar línea
`p`                   # Pegar después
`P`                   # Pegar antes
```
---

## 🪟 Gestión de Ventanas

```bash
`Ctrl+h`              # Ir a ventana izquierda
`Ctrl+j`              # Ir a ventana abajo
`Ctrl+k`              # Ir a ventana arriba
`Ctrl+l`              # Ir a ventana derecha
`<leader>-`           # Split horizontal
`<leader>\|`          # Split vertical
`<leader>wd`          # Cerrar ventana
```
---

## 📑 Gestión de Buffers (Archivos abiertos)

```bash
`Shift+h`             # Buffer anterior
`Shift+l`             # Buffer siguiente
`<leader>bd`          # Cerrar buffer actual
`<leader>bD`          # Cerrar buffer forzado
`<leader>bb`          # Lista de buffers
```
---

## 💻 Terminal

```bash
`<leader>ft`          # Abrir terminal flotante
`<leader>fT`          # Abrir terminal en split
`Ctrl+\`              # Toggle terminal
```

---

## 🔎 Movimiento Rápido

```bash
`gg`                  # Ir al inicio del archivo
`G`                   # Ir al final del archivo
`0`                   # Ir al inicio de la línea
`$`                   # Ir al final de la línea
`w`                   # Siguiente palabra
`b`                   # Palabra anterior
`{`                   # Párrafo anterior
`}`                   # Siguiente párrafo
`Ctrl+u`              # Media página arriba
`Ctrl+d`              # Media página abajo
`zz`                  # Centrar cursor en pantalla
```
---

## 🔧 LSP (Autocompletado y análisis de código)

```bash
`gd`                  # Ir a definición
`gr`                  # Ver referencias
`K`                   # Ver documentación (hover)
`<leader>ca`          # Acciones de código
`<leader>cr`          # Renombrar variable/función
`<leader>cf`          # Formatear código
`]d`                  # Siguiente error
`[d`                  # Error anterior
```
---

## 🔍 Búsqueda y Reemplazo
```bash
`/palabra`            # Buscar palabra
`n`                   # Siguiente ocurrencia
`N`                   # Ocurrencia anterior
`*`                   # Buscar palabra bajo cursor
`:%s/viejo/nuevo/g`   # Reemplazar en todo el archivo
`:%s/viejo/nuevo/gc`  # Reemplazar con confirmación
```
---

## 💡 Útiles de LazyVim

```bash
`<leader>l`           # Lazy (gestor de plugins)
`<leader>ui`          # Toggle UI elements
`<leader>ub`          # Toggle background
`<leader>uw`          # Toggle word wrap 
`<leader>ul`          # Toggle line numbers
`<leader>qq`          # Salir de todo
```
---

## 📋 Guardar y Salir

```bash
`:w`                  # Guardar
`:q`                  # Salir
`:wq` o `:x`          # Guardar y salir
`:q!`                 # Salir sin guardar
`ZZ`                  # Guardar y salir (modo normal)
`<leader>w`           # Guardar (atajo LazyVim)
```
---

## 🎯 Comandos Visuales

```bash
`v`                   # Modo visual (selección)
`V`                   # Modo visual línea
`Ctrl+v`              # Modo visual bloque
`y`                   # Copiar selección
`d`                   # Cortar selección
`>`                   # Indentar derecha
`<`                   # Indentar izquierda
```
---

## 🚀 Productividad Extra

```bash
`<leader>sn`          # Toggle spell check
`<leader>gg`          # Abrir LazyGit
`gc`                  # Comentar línea/selección
`gcc`                 # Comentar línea actual
`.`                   # Repetir último comando
```
---

## 💡 Tips Importantes

1. **Presiona `Space` y espera** - verás un menú con todas las opciones disponibles
2. **`:checkhealth`** - verifica que todo funciona correctamente
3. **Personalizar atajos** - en `~/.config/nvim/lua/config/keymaps.lua`
4. **Ayuda integrada** - `:help <comando>` para cualquier comando de Vim

---

## 🐧 Comandos Útiles de Ubuntu (Terminal)

### Gestión de Archivos
```bash
mv archivo.txt destino/          # Mover archivo
mv nombre_viejo nombre_nuevo     # Renombrar
cp archivo.txt destino/          # Copiar
rm archivo.txt                   # Eliminar archivo
rm -r carpeta/                   # Eliminar carpeta con contenido
rmdir carpeta_vacia/             # Eliminar carpeta vacía
```

### Navegación
```bash
pwd                              # Ver directorio actual
ls                               # Listar archivos
ls -la                           # Listar con detalles y ocultos
cd directorio/                   # Cambiar directorio
cd ..                            # Subir un nivel
cd ~                             # Ir a home
```

### Docker
```bash
docker compose version           # Verificar Docker Compose
docker --version                 # Verificar Docker
docker ps                        # Contenedores activos
docker compose up -d             # Levantar servicios
docker compose down              # Detener servicios
```

---

**Creado por:** Ricard Bausili
**Fecha:** Noviembre 2025
