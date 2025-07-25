# Design Playground - Landkreis Gießen Wegweiser

Dies ist eine Kopie des Hauptprojekts für sichere Design-Experimente.

## Was ist das?

Dieser Ordner enthält eine vollständige Kopie der Landkreis Gießen Wegweiser-Anwendung, die du für Design-Experimente verwenden kannst, ohne das Hauptprojekt zu beeinträchtigen.

## Verwendung

1. **Lokale Entwicklung**: 
   - Öffne `index.html` direkt im Browser
   - Oder verwende einen lokalen Server für bessere Entwicklungserfahrung

2. **Live Server (VS Code)**:
   - Installiere die "Live Server" Erweiterung
   - Rechtsklick auf `index.html` → "Open with Live Server"

3. **Design-Änderungen**:
   - Alle CSS-Stile sind in der `<style>`-Sektion in `index.html`
   - JavaScript-Funktionalität ist im `<script>`-Bereich
   - Karten-Koordinaten und Gebäude-Marker sind im JavaScript definiert

## Unterschiede zum Hauptprojekt

- Im Titel steht "DESIGN PLAYGROUND" zur Unterscheidung
- Ansonsten identisch mit der aktuellen Produktionsversion

## Nächste Schritte

Wenn du diesen Playground als separates Git-Repository einrichten möchtest:

```powershell
cd design-playground
git init
git add .
git commit -m "Initial commit - Design playground"
git remote add origin <neues-repository-url>
git push -u origin main
```

## Aktueller Stand

Diese Version basiert auf dem Stand vom aktuellen Hauptprojekt mit:
- Optimierte mobile Header-Abstände (40px top padding)
- Verfeinerte Sprachauswahl (8px rechter Innenabstand)
- Angepasste Globus-Icon-Größe (18x18px)
- Alle aktuellen Übersetzungen und Funktionen

Viel Spaß beim Experimentieren! 🎨
