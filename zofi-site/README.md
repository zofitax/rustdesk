# Sitio de ZofiDesk (app.zofi.tax)

Páginas estáticas a las que enlaza la aplicación. Se suben tal cual a la raíz de `https://app.zofi.tax/`.

| Archivo | Enlazado desde |
|---|---|
| `privacy.html` | Pantalla de instalación de Windows y Ajustes → Acerca de |
| `docs/mac-permisos.html` | Botón "Ayuda" de los avisos de permisos en Mac |
| `download.html` | Página para compartir con clientes |

Antes de publicar `privacy.html`, completa los campos entre corchetes (`[RAZÓN SOCIAL]`, `[RUC]`, etc.) y haz que la revise un asesor legal.

`download.html` busca los instaladores en el release `zofi` de GitHub. Si publicas los builds con otra etiqueta, cambia `TAG` en el script de la página.
