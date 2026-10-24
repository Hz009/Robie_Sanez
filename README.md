# Portafolio de Robie Sánez

Trabajo de HTML5 y CSS3. El sitio es estático: no usa JavaScript ni un servidor.

## Direcciones

- Repositorio de GitHub: https://github.com/Hz009/Robie_Sanez
- Sitio en GitHub Pages: https://hz009.github.io/Robie_Sanez/

El repositorio es público, para que se pueda ver el proyecto y la web.

## Estructura

```text
index.html
views/
  portfolio.html
  presupuesto.html
  contacto.html
css/
  styles.css
images/
  logo-hs.svg
  favicon.svg
  icono-menu.svg
  icono-linkedin.svg
  icono-instagram.svg
  mapa-sevilla.png
  robie-linguameeting.png
  sevilla-guadalquivir.jpg
  practicas/
README.md
```

`index.html` está en la raíz. Desde `views/`, el CSS y las imágenes van con `../`.

## Verlo en el ordenador

1. Abre `index.html`.
2. Recorre Inicio, Prácticas, Solicitar información y Contacto.
3. Estrecha la ventana para ver el menú de móvil.
4. En Solicitar información, pulsa el botón con campos vacíos: el navegador no deja enviar. Aunque el formulario sea válido, el mensaje no se envía ni se guarda. Lo dice la línea bajo el botón.

## Publicar

Sube el contenido de esta carpeta a la raíz del repositorio: `index.html`, `views/`, `css/`, `images/` y este `README.md`.

En el repositorio, abre Settings, Pages. En Build and deployment elige Deploy from a branch. En Branch elige `main` y la carpeta `/ (root)`.

GitHub Pages solo sirve archivos. El formulario usa `method="get"`. Si el navegador lo acepta, el texto queda en la barra de direcciones y no llega a ningún sitio.
