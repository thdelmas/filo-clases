# Clases con Branca

Sitio de una página para las clases de portugués europeo, francés e inglés.
Un solo archivo: `index.html`. Sin dependencias, sin fuentes externas, sin JavaScript.

## Antes de publicar

Rellenar los campos marcados con `<mark class="todo">` en `index.html`:

- Nombre y apellido (cabecera y pie)
- Ciudad / zona (dos veces)
- Número de WhatsApp: sustituir `34XXXXXXXXX` en los dos enlaces `wa.me` y en el bloque de contacto
- Correo: sustituir `correo@ejemplo.com` (enlace mailto y bloque de contacto)
- Horario de viernes y sábado
- Precio por hora

Después borrar el `<aside class="draft">` y el bloque CSS `.draft` / `mark.todo`.

Comprobación: `grep -c 'todo' index.html` debe dar 0.

## Publicar gratis

Opciones por orden de preferencia (operador asociativo antes que empresa):

1. Codeberg Pages (asociación sin ánimo de lucro, Alemania). Repo público llamado `pages`, rama `main`, `index.html` en la raíz. URL: `https://<usuario>.codeberg.page/`.
2. GitHub Pages. Repo público, Settings > Pages > Deploy from branch `main` / root. URL: `https://<usuario>.github.io/<repo>/`.

Dominio propio opcional más adelante (un `.es` o `.pt` cuesta unos 10 € al año).
