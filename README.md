# PokeApp

Pokédex hecha con HTML, CSS y JavaScript. TP 9 – FSD 2026.

## Cómo abrirla

Usa módulos de JavaScript, así que hay que abrirla con un servidor local:
Live Server en VS Code, o `python -m http.server 8000` y entrar a http://localhost:8000.

## Administrador de prueba

usuario `admin` · contraseña `admin`

## Archivos

- `index.html`: página base
- `css/style.css`: estilos
- `js/datos.js`: datos iniciales (Pokémon, usuario admin, escenas de la batalla)
- `js/app.js`: navegación, vistas, usuarios, carga de Pokémon, batalla y localStorage

## Qué hace

- Pokédex con 10 Pokémon y vista de detalle (con versión shiny)
- Registro e inicio de sesión; el administrador puede cargar nuevos Pokémon
- Batalla por turnos con barras de vida y daño por golpe
- Los datos se guardan con JSON y `localStorage`, así que siguen al cerrar y abrir la app

## Flujo de datos

datos → JavaScript → formularios → eventos → DOM → interacción → JSON → localStorage → aplicación

## Ver la app online (GitHub Pages)

En el repositorio: Settings → Pages → Branch `main` / carpeta `/ (root)` → Save.
