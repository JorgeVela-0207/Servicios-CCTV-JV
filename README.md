# Servicios CCTV JV

Sitio web estático para **Servicios CCTV JV**: instalación de cámaras de seguridad y videovigilancia para casa y pequeños negocios.

## Contenido del repositorio

```
CCVT-WEB/
├── index.html      # Página principal (landing CCTV)
├── styles.css      # Estilos de index.html
├── script.js       # Animaciones de entrada
├── P.html          # Borrador/prototipo de página de soporte TI
├── img/            # Logos, hero e imágenes de marcas
└── README.md
```

## Ver el sitio en local

Abre `index.html` directamente en el navegador, o usa un servidor local:

```bash
# Con Python (si lo tienes instalado)
python -m http.server 8080
```

Luego visita: `http://localhost:8080`

## Subir a GitHub manualmente

### Opción A — Desde la web de GitHub

1. Entra a [github.com](https://github.com) e inicia sesión.
2. Clic en **New repository**.
3. Nombre sugerido: `ccvt-web` o `servicios-cctv-jv`.
4. Deja el repositorio **público** (necesario para GitHub Pages gratuito).
5. **No** marques “Add a README file” (ya existe uno en la carpeta).
6. Clic en **Create repository**.
7. En la pantalla del repo nuevo, elige **uploading an existing file**.
8. Arrastra toda la carpeta del proyecto (o selecciona todos los archivos y la carpeta `img/`).
9. Escribe un mensaje de commit, por ejemplo: `Sitio inicial Servicios CCTV JV`.
10. Clic en **Commit changes**.

### Opción B — Con Git en la terminal

Desde la carpeta del proyecto:

```bash
git init
git add .
git commit -m "Sitio inicial Servicios CCTV JV"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/NOMBRE-DEL-REPO.git
git push -u origin main
```

Sustituye `TU_USUARIO` y `NOMBRE-DEL-REPO` por los tuyos.

## Publicar con GitHub Pages (opcional)

1. En el repositorio de GitHub: **Settings** → **Pages**.
2. En **Source**, elige **Deploy from a branch**.
3. Branch: **main**, carpeta: **/ (root)**.
4. Guarda. En unos minutos el sitio estará en:

   `https://TU_USUARIO.github.io/NOMBRE-DEL-REPO/`

## Contacto en el sitio

Los botones de WhatsApp apuntan al número **+52 868 363 8812**.  
Si cambias el número, actualiza los enlaces `wa.me` en `index.html`.

## Notas

- `P.html` es un prototipo aparte (JV Soporte Técnico TI) y no es la página principal.
- No se requiere Node.js, npm ni build: es HTML, CSS y JavaScript puro.
