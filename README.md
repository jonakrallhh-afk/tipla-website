# tipla-website

Website für TIPLA unter https://tipla.app – gebaut mit [Astro](https://astro.build), gehostet auf Netlify.

## Aufbau

- `src/pages/` – die einzelnen Seiten (`index.astro` = Startseite)
- `src/layouts/Base.astro` – gemeinsames Grundgerüst (Kopfbereich, Farben, Schrift)
- `public/` – statische Dateien wie das Favicon
- `netlify.toml` – Build-Einstellungen und Weiterleitung www → tipla.app

## Lokal starten

```bash
npm install
npm run dev
```

## Veröffentlichen

Jeder Push auf `main` wird von Netlify automatisch gebaut und live gestellt.
Änderungen laufen über einen eigenen Branch und eine Vorschau, bevor sie auf `main` landen.
