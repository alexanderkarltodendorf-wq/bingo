# Bingo Spiel

Eine browserbasierte Bingo-Anwendung, die es Benutzern ermöglicht, Bingo-Spiele zu definieren, Karten zu drucken und Ziehungen im Vollbildmodus durchzuführen.

## Funktionen

### Schritt 1: Spiel definieren und Karten erstellen
- ✅ Einstellbare Rastergröße (3x3 bis 7x7)
- ✅ Einstellbare Anzahl der Karten (1-20)
- ✅ Benutzerdefinierte Begriffe/Wörter (ein Begriff pro Zeile)
- ✅ Optionales freies Feld in der Mitte
- ✅ Automatische Validierung der Mindestanzahl an Begriffen
- ✅ Zufällige Verteilung der Begriffe auf den Karten (Fisher-Yates Shuffle)
- ✅ Druckoptimiertes Kartenlayout
- ✅ Visuelle Vorschau aller generierten Karten

### Schritt 2: Ziehung im Vollbildmodus
- ✅ Vollbildmodus mit prominenter Anzeige des aktuellen Zugs
- ✅ Großer "Ziehen"-Button für einfache Interaktion
- ✅ Zufällige Auswahl ohne Wiederholung
- ✅ Statistikanzeige (gezogen vs. verbleibend)
- ✅ Historie der bereits gezogenen Begriffe
- ✅ Exit-Button zum Zurückkehren zur Hauptansicht
- ✅ Tastaturunterstützung (ESC zum Beenden)

## Verwendung

1. Öffnen Sie `index.html` in einem modernen Webbrowser
2. Geben Sie die gewünschte Rastergröße ein (z.B. 5 für 5x5)
3. Geben Sie die Anzahl der zu erstellenden Karten ein
4. Geben Sie die Begriffe ein (ein Begriff pro Zeile)
5. Optional: Aktivieren Sie "Freies Feld in der Mitte"
6. Klicken Sie auf "Karten erstellen"
7. Drucken Sie die Karten mit dem "🖨️ Karten drucken" Button
8. Starten Sie die Ziehung mit "▶️ Ziehung starten"
9. Klicken Sie auf "Ziehen", um Begriffe zu ziehen

## Technische Details

- **Einzelne HTML-Datei** mit eingebettetem CSS und JavaScript
- **Keine externen Abhängigkeiten** erforderlich
- **Responsive Design** für verschiedene Bildschirmgrößen
- **Druckoptimiert** für die Kartenausgabe
- **Fisher-Yates Shuffle-Algorithmus** für faire Randomisierung

## Browser-Unterstützung

Die Anwendung funktioniert in allen modernen Webbrowsern:
- Chrome/Edge (empfohlen)
- Firefox
- Safari
- Opera

## Lizenz

Siehe LICENSE-Datei für Details.