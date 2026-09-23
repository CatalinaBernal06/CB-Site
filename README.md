# catalina bernal.

Sitio personal de Catalina Bernal: IA responsable e inteligencia financiera.

## Estructura

```
index.html        la página completa (5 pestañas, español e inglés)
favicon.svg       ícono de la pestaña del navegador
404.html          redirige al inicio si alguien entra a una dirección que no existe
.nojekyll         le dice a GitHub que publique los archivos tal cual
img/
  hero.jpg        retrato del inicio
  sobre-mi.jpg    foto de la pestaña "sobre mí"
  contacto.jpg    foto de la pestaña "contacto"
  og-image.jpg    imagen que aparece al compartir el enlace (LinkedIn, WhatsApp)
```

## Enlaces útiles

- Inicio: `https://TU-USUARIO.github.io/`
- Servicios: `https://TU-USUARIO.github.io/#servicios`
- Servicios en inglés: `https://TU-USUARIO.github.io/?lang=en#servicios`

## Cómo editar

- Textos en español: buscar `data-l="es"` en `index.html`. Los de inglés están justo al lado con `data-l="en"`.
- Tarjetas de servicios: están en el `<script>` al final, en `DETECT` y `RESP`.
- Para cambiar una foto, reemplaza el archivo en `img/` con el mismo nombre.
