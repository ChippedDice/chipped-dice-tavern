# Chipped Dice Tavern – Website

Website des Chipped Dice Tavern Rollenspiel e.V. im Stil eines Fantasy-Regelbuchs („Das Tavernenbuch“).
Pures HTML/CSS, kein Build-Schritt nötig. Gehostet über GitHub Pages (siehe `CNAME`).

## Struktur

```
index.html                  Startseite (Kapitel 1, Kapitel 2, Anhang A)
rollenspiel/index.html      Was ist Pen & Paper?
veranstalter/index.html     Angebot für Veranstalter
verein/index.html           Der Verein & Vorstand
conventions/index.html      Termine & Discord
kontakt/index.html          Kontakt, Impressum, Datenschutz
assets/css/style.css        Gemeinsames Stylesheet (Farben als CSS-Variablen oben)
assets/images/              Komprimierte Fotos (max. 1400 px) + Logo + Favicon
assets/Icons/               Logo-Original und Dice-Kun-Icons
```

## Pflege

- **Termine ändern:** Tabelle „Kommende Reiseziele“ in `index.html` und `conventions/index.html`.
- **Neue Fotos:** vorher auf max. ca. 1400 px Breite verkleinern und nach `assets/images/` legen.
  Der Ordner `images/` (Rohfotos) ist per `.gitignore` vom Repo ausgeschlossen.
- **Farben:** in `assets/css/style.css` unter `:root`.

## Lokal ansehen

`index.html` einfach im Browser öffnen.
