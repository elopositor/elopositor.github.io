# Web de presentacion

Pagina personal de Alejandro Valero Collante, publicada en GitHub Pages.

- `index.html` — la pagina entera: el CSS, el JS y las imagenes van dentro del propio
  fichero, asi que no depende de nada externo salvo las fuentes de Google.
- `og.png` — vista previa al compartir el enlace (WhatsApp, LinkedIn).
- `robots.txt` y la etiqueta `noindex` piden a los buscadores que no la listen.
  **Para que Google la encuentre:** quitar la linea `Disallow: /` de `robots.txt` y la
  etiqueta `<meta name="robots">` de `index.html`.

Para cambiar algo, se edita `index.html` y se hace push: GitHub Pages republica solo.
