# Forshore: Tide Rescue · Web para GitHub Pages

Inicio, soporte y privacidad en español e inglés. HTML y CSS estáticos, sin instalación ni compilación. El juego todavía no se ha publicado: la portada indica «Próximamente en el App Store».

Contacto incorporado: **Jared Pérez Vega · jared.perez.vega@icloud.com**.

El nombre confirmado en App Store Connect es **Forshore: Tide Rescue**. La web usa el nombre completo en títulos, metadatos, cabecera y pie; «Forshore» se mantiene como forma breve dentro de los textos. El repositorio `jpv88/forshore-web` y todas sus URLs siguen siendo los mismos.

## Actualizar la web

1. Utiliza el repositorio existente **`jpv88/forshore-web`**. La web anterior ya está publicada; este paquete prepara la actualización 0.18.2 con el nombre confirmado, la continuación entre dispositivos y la reactivación explícita de iCloud.
2. Sube **el contenido de esta carpeta**, con `index.html` en la raíz del repositorio. Conserva las carpetas `en` y `assets`. El ZIP independiente ya contiene esta estructura. No subas el proyecto iOS completo al repositorio de la web.
3. En el repositorio, abre **Settings → Pages**. Elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y guarda.
4. Cuando GitHub termine, abre la dirección que muestra Pages y comprueba inicio, soporte, privacidad y el cambio de idioma desde un iPhone.

El método se documenta en la [guía oficial de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site). GitHub Free permite usar Pages desde repositorios públicos; otros planes también lo permiten desde repositorios privados. Las páginas publicadas son públicas.

## Direcciones de la ficha de Apple

Las URLs confirmadas están incorporadas a `Release/metadata.json` del proyecto iOS. No se ha añadido enlace de descarga porque la app aún no está publicada.

| Uso | Español | Inglés |
|---|---|---|
| Portada | https://jpv88.github.io/forshore-web/ | https://jpv88.github.io/forshore-web/en/index.html |
| Soporte | https://jpv88.github.io/forshore-web/soporte.html | https://jpv88.github.io/forshore-web/en/support.html |
| Privacidad | https://jpv88.github.io/forshore-web/privacidad.html | https://jpv88.github.io/forshore-web/en/privacy.html |

Las seis páginas anteriores respondieron correctamente en la comprobación de la entrega 0.18.0. **Este ZIP actualizado con el nombre Forshore: Tide Rescue y el contenido de iCloud está pendiente de subir a GitHub:** sustituye los HTML y `styles.css` en el repositorio cuando vayas a distribuir la versión que incorpora esa función y vuelve a comprobar las seis direcciones. Los enlaces relativos permiten alojar también en un dominio propio, pero no hace falta.

## Contenido y mantenimiento

Las páginas de ayuda y privacidad se generan desde `Support/*.md` del proyecto Forshore mediante `python3 Scripts/build_website.py`. La portada y la estructura compartida se editan en ese script; el diseño, en `Website/styles.css`. El icono procede del arte del propio juego. El resultado se puede abrir directamente con `index.html` o servir con cualquier servidor estático.

El script no es necesario para alojar el ZIP independiente. Si editas sus HTML directamente, conserva esos cambios antes de regenerar desde el proyecto.

Antes de publicar la política, revisa que la gestión del buzón siga el criterio propuesto: usar las consultas para soporte, conservarlas mientras se resuelve el caso y su seguimiento, y después solo cuando proceda por obligaciones o reclamaciones. No se ha configurado borrado automático del correo ni examinado el buzón. La política describe el guardado privado y opcional de iCloud, iCloud Mail, Game Center voluntario y los registros de seguridad de GitHub Pages; no afirma ausencia absoluta de tratamiento.

La web no incorpora JavaScript, formularios, fuentes externas, analítica, publicidad ni cookies propias. Incluye navegación por teclado, enlace para saltar al contenido, adaptación a móvil y colores claros/oscuros. La versión anterior está publicada; la actualización incluida y la revisión visual en un navegador de iPhone siguen pendientes.
