# Forshore · Web para GitHub Pages

Inicio, soporte y privacidad en español e inglés. HTML y CSS estáticos, sin instalación ni compilación. El juego todavía no se ha publicado: la portada indica «Próximamente en el App Store».

Contacto incorporado: **Jared Pérez Vega · jared.perez.vega@icloud.com**.

## Publicar

1. Crea o utiliza un repositorio para la web, por ejemplo `forshore-web`.
2. Sube **el contenido de esta carpeta**, con `index.html` en la raíz del repositorio. Conserva las carpetas `en` y `assets`. El ZIP independiente ya contiene esta estructura. No subas el proyecto iOS completo al repositorio de la web.
3. En el repositorio, abre **Settings → Pages**. Elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y guarda.
4. Cuando GitHub termine, abre la dirección que muestra Pages y comprueba inicio, soporte, privacidad y el cambio de idioma desde un iPhone.

El método se documenta en la [guía oficial de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site). GitHub Free permite usar Pages desde repositorios públicos; otros planes también lo permiten desde repositorios privados. Las páginas publicadas son públicas.

## Direcciones de la ficha de Apple

Falta conocer el usuario u organización y el nombre del repositorio. No se han inventado URLs ni añadido enlaces de descarga de una app que aún no está publicada.

| Uso | Ruta dentro de la web |
|---|---|
| Portada ES / EN | `index.html` / `en/index.html` |
| Soporte ES / EN | `soporte.html` / `en/support.html` |
| Privacidad ES / EN | `privacidad.html` / `en/privacy.html` |

Cuando estén en línea, copia las URLs completas en `Release/metadata.json` del proyecto iOS y añade los enlaces definitivos a sus Ajustes. Los enlaces relativos ya funcionan tanto en una web de repositorio como en un dominio propio; este último no es necesario.

## Contenido y mantenimiento

Las páginas de ayuda y privacidad se generan desde `Support/*.md` del proyecto Forshore mediante `python3 Scripts/build_website.py`. La portada y la estructura compartida se editan en ese script; el diseño, en `Website/styles.css`. El icono procede del arte del propio juego. El resultado se puede abrir directamente con `index.html` o servir con cualquier servidor estático.

El script no es necesario para alojar el ZIP independiente. Si editas sus HTML directamente, conserva esos cambios antes de regenerar desde el proyecto.

Antes de publicar la política, revisa que la gestión del buzón siga el criterio propuesto: usar las consultas para soporte, conservarlas mientras se resuelve el caso y su seguimiento, y después solo cuando proceda por obligaciones o reclamaciones. No se ha configurado borrado automático del correo ni examinado el buzón. La política describe iCloud Mail, Game Center voluntario y los registros de seguridad de GitHub Pages; no afirma ausencia absoluta de tratamiento.

La web no incorpora JavaScript, formularios, fuentes externas, analítica, publicidad ni cookies propias. Incluye navegación por teclado, enlace para saltar al contenido, adaptación a móvil y colores claros/oscuros. No se ha publicado ni se ha verificado todavía en un navegador de iPhone.
