# So funktioniert ein thermisches Kraftwerk

Interaktives Schaubild des geschlossenen Wasser-Dampf-Kreislaufs eines thermischen
Kraftwerks – gedacht als Unterrichtsmaterial für 14- bis 18-Jährige.

## Öffnen

`index.html` im Browser öffnen. Mehr braucht es nicht: eine einzige Datei, kein Build,
keine Abhängigkeiten außer den Webfonts von Google Fonts (ohne Netz greifen die
Fallback-Schriften).

## Inhalt

Sechs Stationen im Kreis – Brennkammer/Kessel, Überhitzer, Turbine, Generator,
Kondensator, Speisewasserpumpe – verbunden durch animierte Rohrleitungen. Jede Station
lässt sich anklicken und öffnet einen Infokasten mit Erklärung, Kennzahlen und einem
Alltagsvergleich. Der Play-Button in der Mitte startet eine geführte Tour durch alle
sechs Stationen. Unten zeigt eine Leiste, wohin die eingesetzte Energie geht
(ca. 40 % Strom, ca. 60 % Abwärme).

Farbsystem: Rot/Orange = Wärme und heißer Dampf, Blau = Wasser und Kühlung,
Grau = mechanische Energie, Gelb = elektrische Energie.

## Bedienung

| Eingabe | Wirkung |
|---|---|
| Klick auf eine Station | Infokasten öffnen |
| `Tab` | durch die Stationen springen |
| `Enter` / `Leertaste` | Infokasten öffnen |
| `Esc` oder Klick daneben | Infokasten schließen |

Getestet für Desktop (ab 1024 px) und Tablet (ab 768 px).
`prefers-reduced-motion` wird respektiert.
