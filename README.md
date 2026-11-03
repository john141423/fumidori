# Web de presentación de Fumidori

**Publicada en:** https://john141423.github.io/fumidori/ (repositorio público https://github.com/john141423/fumidori, GitHub Pages desde `main`). Para actualizarla: `npm run presentacion`, commit y `npm run presentacion:publicar`.

Web estática (HTML y CSS, sin JavaScript, sin cookies ni recursos de otros dominios) en español (`index.html`) e inglés (`en/index.html`), con:

- portada con capturas reales de la app;
- funciones y el plan para cada objetivo;
- sección «Para escuelas», con los dossieres en PDF (`escuelas/`, en español, inglés y japonés);
- privacidad (enlaza a https://john141423.github.io/fumidori-privacy/), preguntas frecuentes y contacto.

No se edita a mano. Los textos están en `scripts/presentacion.mjs`; para regenerarla, desde la carpeta del proyecto:

```
npm run presentacion
```

Eso vuelve a crear la web, las fuentes recortadas, las capturas (a partir de `store/capturas-app`, que genera `npm run ficha`) y los tres PDF de `escuelas/`.

Para verla sin publicarla: doble clic en `index.html`.

## Publicarla gratis en GitHub Pages

Igual que la web de privacidad, en un repositorio público propio (por ejemplo, `fumidori`), con GitHub Pages desde la rama `main` y la carpeta raíz. La dirección sería `https://john141423.github.io/fumidori/`.

Cuando Fumidori esté en Google Play, cambia en `scripts/presentacion.mjs` el botón «Próximamente en Google Play» por el enlace a la ficha y vuelve a generar la web.
