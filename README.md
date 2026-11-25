# Atlas geográfico y fotográfico Lima–Satipo 2026

Proyecto académico estudiantil relacionado con la salida de campo Lima–Satipo (UNMSM). **No es un sitio oficial de la universidad.**

## Estado actual

El repositorio ya está creado y, hasta que se incorporen los archivos del atlas, **aún no contiene el sitio web publicado**. El paquete completo fue preparado como `Atlas_Lima_Satipo_Web_Publicacion.zip`: 243 fotografías y miniaturas, recorrido GPS, pisos ecológicos, ecorregiones, relieve y perfil altitudinal.

## Cómo cargar el atlas en **este mismo repositorio**

1. Descarga el ZIP del atlas desde la conversación con ChatGPT y **extráelo**.
2. Instala [GitHub Desktop](https://desktop.github.com/) y accede con tu cuenta.
3. En GitHub Desktop, elige **File → Clone repository…** y busca **`pierojesusmoralesfigueroa-a11y/atlas-lima-satipo-2026`**. Usa **Clone**. **No crees otro repositorio.**
4. Abre la carpeta local de ese repositorio (**Repository → Show in Explorer**).
5. Copia **el contenido** de la carpeta extraída (no la carpeta exterior) dentro del repositorio clonado. En la raíz deben quedar `index.html`, `datos.js`, `capas.js`, `ruta.js`, `perfil.js`, `hillshade.png`, `portada.jpg`, `fotos/`, `miniaturas/` y `.nojekyll`. **No elimines `.git`.**
6. En GitHub Desktop revisa los archivos cambiados, escribe un mensaje como **«Agregar atlas interactivo Lima–Satipo»**, haz clic en **Commit to main** y luego **Push origin**.
7. Verifica en GitHub que `index.html` aparezca en la **raíz** del repositorio, no dentro de un ZIP ni de una carpeta adicional.

## Publicación mediante GitHub Pages

**Antes de hacer público el sitio**, revisa los permisos de todos los datos geográficos y la conveniencia de mostrar coordenadas GPS exactas. Aunque las fotos cuentan con permiso indicado para este proyecto, los metadatos de `Ecorregiones_Brack_Corredor` contienen una nota de **«Para uso interno del MINAM»**. El acceso público a datos no es en sí mismo autorización para redistribuir esta capa.

Con los derechos verificados o la capa sustituida por una versión de libre redistribución:

- Si tienes **GitHub Free**, GitHub Pages requiere un repositorio **público**; cambia la visibilidad en **Settings → General → Danger Zone → Change repository visibility**, solo después de la revisión.
- En **Settings → Pages → Build and deployment**, elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y guarda.
- Comprueba el enlace en **Settings → Pages**. La dirección esperada para un sitio de proyecto público es:
  https://pierojesusmoralesfigueroa-a11y.github.io/atlas-lima-satipo-2026/

> Un repositorio privado no garantiza que el sitio publicado sea privado; verifica las opciones y el alcance real de la publicación antes de activar Pages.

## Datos y limitaciones

- 243 fotografías GPS y 243 miniaturas, sujetas a los permisos de exhibición confirmados por el proyecto.
- Ruta SIG de aproximadamente 439,44 km; posiciones y altitudes derivadas de distintas fuentes.
- 13 tramos de pisos ecológicos, algunos con estados **PRELIMINAR** o **REVISAR**.
- Seis categorías de ecorregiones; derechos de redistribución pendientes de confirmar.
- DEM de resolución nominal 30 m, transformado en una imagen ligera de relieve para el navegador.

La web utiliza Leaflet y mapas base externos; requiere acceso a Internet para visualizar esos servicios.

**Documentación:** [Clonar en GitHub Desktop](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop) · [GitHub Pages](https://docs.github.com/en/pages/quickstart)
