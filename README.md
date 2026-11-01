# Portfolio — Jordi Corbalan Vilaplana

Web personal de recerca en machine learning, experiència professional i projectes.

**Web:** https://jcorbalanv.github.io

## Desenvolupament local

Web estàtica amb HTML i CSS, sense dependències de compilació ni JavaScript. Les tipografies DM Sans i Instrument Serif es carreguen de Google Fonts, amb fonts del sistema com a alternativa.

```sh
python3 -m http.server 4173
```

Obre http://localhost:4173. El disseny s’adapta a mòbil, tauleta i escriptori i inclou estils d’impressió, navegació per teclat i suport per a moviment reduït.

## Contingut

- `index.html`: perfil, recerca, experiència, projectes, formació i contacte.
- `styles.css`: disseny i adaptació a diferents pantalles.
- `assets/`: il·lustració de dades original en SVG i favicon.

El perfil es basa en el CV facilitat; els projectes addicionals es conserven de la web anterior. Cal actualitzar manualment les dates i l’estat de les publicacions quan canviïn.

## Desplegament

GitHub Pages publica el repositori des de la branca `main`. Els PDF dels currículums es conserven localment i s’exclouen del repositori amb `.gitignore`.
