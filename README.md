# Arbeitszeiterfassungstool

Ein einfaches und benutzerfreundliches Arbeitszeiterfassungstool für den Browser, das es ermöglicht, Arbeitszeiten zu erfassen, zu verwalten und zu exportieren. Ideal für Freiberufler, Selbstständige oder kleine Teams, die ihre Arbeitszeiten ohne komplexe Software im Blick behalten möchten.

## 📋 Funktionen

- **Arbeitszeit hinzufügen**: Erfassen Sie Datum, Startzeit, Endzeit und Pausendauer für jeden Arbeitstag
- **Automatische Berechnung**: Die Arbeitszeit wird basierend auf Ihren Eingaben automatisch berechnet
- **Übersicht**:
  - **Wöchentliche, monatliche und jährliche Gesamtstunden** werden angezeigt
  - **Arbeitsstunden nach Kalenderwoche**: Zeigt die Summe der Arbeitsstunden pro Kalenderwoche an
  - **Arbeitsstunden nach Monat**: Zeigt die Summe der Arbeitsstunden pro Monat an
- **Einträge bearbeiten und löschen**: Verwalten Sie Ihre erfassten Arbeitszeiten direkt in der Tabelle
- **Alle Einträge zurücksetzen**: Möglichkeit, alle erfassten Daten zu löschen und von vorne zu beginnen
- **Datenexport**:
  - **Teilen per E-Mail oder WhatsApp**: Exportieren Sie Ihre Arbeitszeiten für einen ausgewählten Zeitraum und teilen Sie sie direkt
  - **Gesamtarbeitszeit und Zeitraum**: Der Export enthält den ausgewählten Zeitraum und die Gesamtarbeitszeit
- **Responsive Design**: Optimiert für die Nutzung auf Smartphones und Tablets

## 🚀 Installation

1. **Repository klonen oder herunterladen**:

   ```bash
   git clone https://github.com/tobwil/arbeitszeiterfassung.git
2. **Dateien öffnen**:

Öffnen Sie die Datei `index.html` in Ihrem bevorzugten Browser.

> **Hinweis:** Da das Tool vollständig clientseitig ist, ist keine zusätzliche Installation oder Server erforderlich

## 📖 Anleitung

### Arbeitszeit erfassen:

1. Geben Sie im Abschnitt **"Arbeitszeit eingeben"** das Datum, die Start- und Endzeit sowie die Pausendauer in Minuten ein
2. Klicken Sie auf **"Hinzufügen"**, um die Arbeitszeit zu speichern

### Einträge verwalten:

- In der Tabelle können Sie Ihre Einträge sehen
- Verwenden Sie die Symbole 🖋️ (Bearbeiten) und 🗑️ (Löschen), um Einträge zu verwalten

### Übersicht ansehen:

- Die Übersicht zeigt Ihre Gesamtarbeitszeit für die aktuelle Woche, den aktuellen Monat und das aktuelle Jahr
- Zusätzlich werden Ihre Arbeitsstunden nach Kalenderwoche und Monat zusammengefasst

### Daten teilen:

1. Wählen Sie im Abschnitt **"Zeitraum auswählen und teilen"** den gewünschten Zeitraum aus
2. Klicken Sie auf **"Per E-Mail teilen"** oder **"Per WhatsApp teilen"**, um die Daten zu exportieren
3. Die exportierte Nachricht enthält den Zeitraum, die Gesamtarbeitszeit und eine Auflistung der Einträge

### Alle Einträge zurücksetzen:

- Klicken Sie auf **"Alle Einträge zurücksetzen"**, um alle erfassten Daten zu löschen

## ⚠️ Hinweise

- **Datenspeicherung:** Die erfassten Daten werden im Local Storage des Browsers gespeichert. Wenn Sie den Browser-Cache löschen oder einen anderen Browser verwenden, sind die Daten nicht mehr verfügbar
- **Datenschutz:** Da die Daten lokal gespeichert werden, haben nur Sie Zugriff darauf

## 🛠️ Anpassungen

- **Design-Anpassungen:** Passen Sie das CSS an, um das Erscheinungsbild nach Ihren Wünschen zu gestalten
- **Erweiterungen:** Der JavaScript-Code ist modular aufgebaut und kommentiert, sodass Sie leicht neue Funktionen hinzufügen können
- **Sprachunterstützung:** Derzeit ist das Tool auf Deutsch verfügbar. Sie können es erweitern, um weitere Sprachen zu unterstützen

## 🖥️ Technologien

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**

### 📱 Responsive Design

- Das Tool ist für Desktop- und Mobilgeräte optimiert

## 🙏 Danksagung

- **Icons:** Verwendet wurden Emojis für die Symbole 🖋️ und 🗑️
- **Inspiration:** Dieses Projekt wurde inspiriert durch den Wunsch nach einer einfachen und unkomplizierten Möglichkeit, Arbeitszeiten zu erfassen

## 🌐 Live-Demo

Probieren Sie das Tool hier aus:
