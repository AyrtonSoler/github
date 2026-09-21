# Git y GitHub

Una página con un párrafo sobre Git y GitHub y tres imágenes para practicar durante los dos días
del mini curso de Git y GitHub.

## Abrir el sitio

Abre `index.html` en tu navegador. Edita los archivos, guarda y recarga
la página para ver los cambios. No necesitas instalar nada.

- `index.html`: párrafo introductorio e imágenes.
- `styles.css`: colores, tipografía y distribución adaptable a móvil.
- `imagenes/`: ilustraciones locales de ejemplo; funciona sin conexión.

## Personalizar

Cambia el párrafo directamente en `index.html`.
Para usar una foto, cópiala a `imagenes/` y cambia, por ejemplo,
`src="imagenes/montanas.svg"` por `src="imagenes/mi-foto.jpg"`.
Actualiza también `alt` para describir la nueva imagen.
Puedes duplicar una etiqueta `<img>` para agregar otra imagen.

## Ideas para los demos

**Día 1 — Cambios e historial:** modifica el párrafo, revisa con
`git status` y `git diff`, prepara el archivo con `git add index.html`
y registra la versión con `git commit`. Cambia después el color de `background` en
el CSS para crear otro commit y consultar ambos con `git log --oneline`.
`git diff` muestra cambios en archivos que Git ya sigue; registra primero
una versión inicial de la plantilla.

**Día 2 — Colaboración:** con el repositorio publicado en GitHub, clona
una copia, crea una rama y agrega una imagen o mejora este README.
Publica la rama, abre un pull request, revisa el sitio e integra el cambio.
Vuelve a la rama principal y ejecuta `git pull`. Para practicar un conflicto,
pueden editar la misma línea del párrafo en dos ramas e intentar integrarlas.
