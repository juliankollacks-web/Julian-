# Smart Dart – Website & Renderings

Produktseite im Apple-Stil für die Geschäftsidee **Smart Dart**: die Steeldart-Scheibe mit austauschbaren Feldern.

Öffne `index.html` im Browser. Die Seite lädt nichts aus dem Internet: Schriften und three.js liegen im Ordner `vendor/`, die Lizenztexte in `vendor/licenses/`.

## Vor dem Start

| Punkt | Stand |
|---|---|
| Favicon | erledigt (`favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`) |
| Impressum, Datenschutz, AGB | Entwürfe angelegt. Gelb markierte Angaben ergänzen und rechtlich prüfen lassen |
| Widerrufsbelehrung | fehlt noch, gehört in die AGB oder auf eine eigene Seite |
| Eigene Domain | offen. Domain kaufen, beim Hosting verbinden, HTTPS aktivieren |
| Hosting-Anbieter | offen. Name und Logfile-Dauer in die Datenschutzerklärung eintragen |
| Bestellfunktion | offen. „Konfiguration anfragen“ überträgt noch keine Daten |

## Inhalt der Website

- **Scroll-Animation in 3D:** Scheibe dreht sich, Kamera fährt an die Triple 20, das Feld kommt heraus, die Schichten fliegen auseinander, am Ende wächst der Surround mit LED-Lichtring hervor
- **„Do it smart.“:** Kamerafahrt durch das „o“, gestochen scharf in jeder Zoomstufe
- **Highlights, Farben, Größen, Ersparnis**
- **Surround-Studio:** Größe, Farbe, glänzend oder matt, LED-Lichtring, Texte, bis zu 6 eigene Logos
  - Logos per Tippen oder Ziehen hochladen – die Vorschau zeigt sie sofort
  - Weißer Hintergrund wird automatisch entfernt, dunkle Logos werden auf dunklem Surround in Schriftfarbe gezeigt
- **Konfigurator:** Größe, Farbschema, Drahtspinne, Zahlen, Surround, Ersatzfelder über einen großen Feldwähler (Zahl + Bereich), Preis, Export als PNG mit 4096 × 4096 Pixeln

## Renderings (`renders/`)

| Datei | Inhalt |
|---|---|
| `01-smartdart-turnier.jpg` | Turnier-Scheibe, 4800 × 4800 |
| `02-smartdart-led-lichtring.jpg` | Mit glänzend schwarzem LED-Lichtring |
| `03-smartdart-surround-glanz.jpg` | Mit glänzendem Surround, Logo und Text |
| `04-smartdart-feld-entnommen.jpg` | Triple 20 herausgenommen |
| `05-smartdart-beispiel-verein.jpg` | Beispiel Vereins-Edition (fiktiver Verein) |
| `06-smartdart-beispiel-kneipe.jpg` | Beispiel Kneipen-Edition (fiktive Marke) |
| `07-smartdart-farbvarianten.jpg` | Alle 8 Farbschemata |
| `08-smartdart-groessen.jpg` | Die drei Größen maßstabsgetreu |
| `09-smartdart-3d-feldwechsel.jpg` | 3D: Feld wird herausgezogen |
| `10-smartdart-3d-explosion.jpg` | 3D: alle Schichten |
| `11-smartdart-3d-seitenansicht.jpg` | 3D: Seitenansicht |
| `12-smartdart-3d-surround.jpg` | 3D: Surround mit LED-Lichtring |

## Preise

Aus der Präsentation: Scheibe 74,95 €, Ersatzfeld 9,99 €.
Alle anderen Preise (kleinere Größen, Surround, LED-Lichtring 39,95 €, Farbdesign, Logodruck, Gravur) sind Vorschläge und stehen am Anfang des Skripts in `index.html` (`SIZES`, `RINGS`, `PRICE`).
