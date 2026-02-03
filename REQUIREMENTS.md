# Volleyball Team Manager - Anforderungen

## Funktionale Anforderungen

### 1. Spielerverwaltung
- ✅ Spieler per Eingabefeld hinzufügen
- ✅ Spielernamen anzeigen (als Tags/Chips)
- ✅ Einzelne Spieler löschen können (X-Button auf dem Tag)
- ✅ Alle Spieler auf einmal löschen können
- ✅ Spielerliste muss persistent gespeichert sein (LocalStorage)

### 2. Team-Organisation (MANUELL - KEINE AUTOMATISCHE TEAMBILDUNG!)
- ✅ Spieler manuell zu Teams zuweisen (per Button/Prompt)
- ✅ Teams erstellen mit "+" Button
- ✅ Teams anzeigen mit farblicher Unterscheidung
- ✅ Spieler zwischen Teams verschieben können (entfernen und erneut hinzufügen)
- ✅ Teams löschen können
- ✅ Aktuelle Team-Konstellation speichern (LocalStorage)

### 3. Persistenz
- ✅ Spielerliste speichern
- ✅ Team-Konstellationen speichern (mehrere Teams möglich)
- ✅ Daten lokal via LocalStorage

## Nicht-funktionale Anforderungen

### UI/UX
- ✅ Modernes, responsives Design (Tailwind CSS)
- ✅ Mobile-first (optimiert für Android-Handy)
- ✅ Intuitive Bedienung ohne Erklärung
- ✅ Schöne Farbscheme mit hohem Kontrast

### Performance
- ✅ Schneller, leichtgewichtiger Code
- ✅ Keine Abhängigkeiten außer Tailwind CSS CDN
- ✅ Sofortiges Laden ohne Compilation

### Wartbarkeit
- ✅ Single-File-Lösung (HTML + CSS + JS in einer Datei)
- ✅ Klarer, lesbarer Code
- ✅ Kommentare für komplexe Logik

## Was wurde entfernt:
- ❌ Automatische Team-Generierung (Shuffle-Funktion)
- ❌ Teamgröße-Selector
- ❌ "Teams bilden" Button

## Neue Features:
- ✅ Teams manuell erstellen und benennen
- ✅ Spieler individuell zu Teams hinzufügen
- ✅ Spieler von Teams entfernen
- ✅ Teams löschen
