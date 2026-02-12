# 🛠 Werkstatt Website Template - Anleitung

Dieses Template (`workshop-template.html`) ist darauf optimiert, schnell und effizient neue Websites für Autowerkstätten zu erstellen. Du musst kein Design anpassen – nur die Daten!

## 🚀 Schnelleinrichtung

1.  **Datei kopieren:** Kopiere die `workshop-template.html` und benenne sie für deinen Kunden um (z.B. `werkstatt-name.html`).
2.  **Konfiguration finden:** Öffne die Datei in einem Texteditor und suche nach dem Bereich `CONFIG`.
3.  **Daten einfügen:**
    *   **Unternehmen:** Name und Markenfarbe (`primaryColor`) ändern.
    *   **Kontakt:** Telefonnummer, E-Mail und Adresse der alten Seite eintragen.
    *   **Services:** Die Leistungen der alten Seite in die Liste kopieren.
    *   **Bilder:** Verlinke lokale Bilder oder nutze die vorhandenen Unsplash-Links.

## 💡 Profi-Tipps zum Ausfüllen

### 1. Die richtigen Icons finden
Das Template nutzt **Google Material Symbols**. Wenn du ein Icon für eine neue Leistung suchst (z.B. Klimaservice):
*   Suche auf [fonts.google.com/icons](https://fonts.google.com/icons?icon.set=Material+Symbols)
*   Kopiere den Namen des Icons (z.B. `ac_unit`) und trage ihn im `icon`-Feld in der `CONFIG` ein.

### 2. Google Maps Integration
Im Kontaktformular ist eine Google Map verlinkt. Such bei Google Maps einfach nach der Adresse und füge den exakten Namen/Adresse im Feld `googleMapsQuery` ein.

### 3. Mobil-Optimierung testen
Das Template hat unten einen **Sticky "Anrufen"-Button** für Handys. Um das zu testen:
*   Öffne die Datei im Browser.
*   Drücke `F12` (Entwicklertools).
*   Klicke auf das Handy-Icon (Device Toolbar) ganz oben links.
*   Aktiviere die "Responsive" Ansicht.

## 🎨 Design-Anpassung
Du musst kein CSS schreiben! Ändere einfach nur den Hex-Code bei `primaryColor`:
*   VW / Audi Blau: `#0047bb`
*   Mercedes Grau: `#2b2b2b`
*   BMW Blau: `#0066b3`
*   Neutrales Werkstatt-Rot: `#e31e24`

---
*Erstellt von Antigravity für effiziente Web-Workflows.*
