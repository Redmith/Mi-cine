# MI CINE

Mi plataforma personal de películas. Los videos se reproducen con el reproductor de Byse mediante iframe; esta página no guarda archivos de video.

## Mi página

https://redmith.github.io/mi-cine/

Repositorio: https://github.com/Redmith/mi-cine

## Estructura

```
mi-cine/
├── index.html    Página web, diseño y funcionalidades
├── catalog.json  Base de datos del catálogo
└── README.md     Estas instrucciones
```

## Instalación

1. Creá el repositorio `mi-cine` en GitHub.
2. Subí `index.html`, `catalog.json` y `README.md`.
3. Activá GitHub Pages: Settings → Pages → Branch `main` / `(root)` → Save.
4. Abrí https://redmith.github.io/mi-cine/

## Agregar películas

1. Subí el video a Byse y copiá el código iframe.
2. En la página, entrá a **Administrar** y completá título, año, género, portada, descripción y el código de inserción.
3. Pegá tu token de GitHub (solo repo `mi-cine`, Contents: Read and write) y tocá **Guardar en GitHub**.
4. El token se mantiene solo en la memoria de la pestaña: no se guarda en ningún archivo.

También podés descargar `catalog.json` desde Administrar y subirlo a mano al repositorio.

## Catálogo de ejemplo

La página arranca con 8 películas de ejemplo. Solo la primera, "El secreto de sus ojos" (2009), trae un iframe de Byse de muestra. Las demás tienen el campo de video vacío: reemplazalas o completalas desde Administrar con tu propio código de Byse.

## Importante

- GitHub Pages es público: el catálogo y sus enlaces los puede ver cualquier visitante.
- GitHub Pages no tiene base de datos privada ni autenticación propia.
