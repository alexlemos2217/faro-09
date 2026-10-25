# Publicación — FARO:09

## GitHub + Netlify (recomendado)

1. Creá un repositorio nuevo y subí `index.html`, `game.js`, `styles.css`, `favicon.svg` y los archivos de documentación.
2. Abrí Netlify y agregá un proyecto a partir de GitHub.
3. Configurá:
   - **Build command:** ninguno.
   - **Publish directory:** `.` (raíz).
   - **Production branch:** la rama donde subiste el juego, por ejemplo `main`.
4. Desplegá y probá tanto el inicio como la interacción y la vista móvil.
5. Cada nuevo commit a la rama configurada disparará un deploy si está activada la integración continua.

No cambies los archivos de los juegos anteriores. FARO:09 es un proyecto independiente.

## Publicación manual

Descomprimí el ZIP y arrastrá **la carpeta que contiene `index.html`** a la sección de deploys del nuevo sitio en Netlify.

## Verificaciones útiles

- Página inicial accesible, sin errores en consola.
- Botones de **Comenzar historia**, **Continuar**, **Registro** y **Pausa**.
- Moverse con `A` / `D` y con los controles táctiles en celular.
- Progreso guardado al recargar después de una interacción.
- Resolución de ambos acertijos, elección final y reinicio de la campaña.
