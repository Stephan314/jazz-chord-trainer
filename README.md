# Jazz Chord Trainer 🎷

Eine interaktive Web-App zum Üben von Jazz-Harmonielehre — Akkordtöne, Umkehrungen und Kadenzen.

🌐 **[Live-Demo](https://DEIN-USERNAME.github.io/jazz-chord-trainer/)**

---

## Features

- **Akkord-Quiz** — Ein Akkord wird angezeigt, du nennst die Töne (Texteingabe oder Klaviatur)
- **Notendarstellung** — Töne werden auf einem Notensystem angezeigt, mit ein/ausblenbaren Tonnamen
- **Klaviatur-Eingabe** — Töne per Mausklick auf einer Klaviatur auswählen
- **Umkehrungen** — Grundstellung, 1., 2. und 3. Umkehrung üben
- **Kadenzen** — II–V–I Dur/Moll, I–VI–II–V und Blues (12-Takte) in allen Tonarten
- **Akkordtypen-Filter** — Beliebige Akkordtypen aktivieren/deaktivieren
- **4 Schwierigkeitsstufen** — Von einfachen Dreiklängen bis zu komplexen alterierten Akkorden
- **Lernstatistik** — Trefferquote gesamt und pro Akkordtyp, dauerhaft gespeichert
- **Audio** — Akkord abspielen via Web Audio API (funktioniert mit jedem Audio-Interface)

---

## Akkordtypen

| Level | Akkordtypen |
|-------|-------------|
| 1 — Grundakkorde | maj7, min7, Dom7, Dur- und Molldreiklang |
| 2 — Erweiterte Akkorde | min7b5, dim7, maj7#11, maj9, 9, min9, 7sus4 |
| 3 — Jazz-Fortgeschritten | 7alt, 13, maj7#5, 7#9, 7b9, min11, 7#11, minMaj9 |
| 4 — Experte | 7#9b13, 13#11, maj7#11#5, 7b9b13, min13 |

---

## Lokal starten

Die App ist eine einzelne HTML-Datei ohne Abhängigkeiten — einfach herunterladen und im Browser öffnen:

```bash
# Repository klonen
git clone https://github.com/DEIN-USERNAME/jazz-chord-trainer.git

# Datei im Browser öffnen
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Keine Installation, kein Build-Schritt, kein Server nötig.

---

## Eingabe-Hinweise

- Töne mit **Leerzeichen** trennen: `C E G B`
- Vorzeichen: `#` für Kreuz, `b` für Be — z.B. `Bb`, `F#`, `Eb`
- Deutsche Notation wird automatisch erkannt: `H` wird als `B` interpretiert
- Enharmonische Verwechslungen werden akzeptiert: `C#` = `Db` ✓

---

## Statistik

Die Lernstatistik wird im `localStorage` des Browsers gespeichert und bleibt über Sessions erhalten. Sie kann im Statistik-Tab zurückgesetzt werden.

---

## Technologie

- Reines HTML/CSS/JavaScript — keine Frameworks, keine Abhängigkeiten
- Web Audio API für die Akkord-Wiedergabe
- SVG für die Notendarstellung
- `localStorage` für persistente Statistik

---

## Hosting auf GitHub Pages

1. Repository als **Public** anlegen
2. `index.html` hochladen
3. **Settings → Pages → Branch: main → Save**
4. App ist erreichbar unter `https://DEIN-USERNAME.github.io/jazz-chord-trainer/`

---

## Lizenz

MIT — frei verwendbar und anpassbar.
