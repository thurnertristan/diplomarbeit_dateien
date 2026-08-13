# diplomarbeit_dateien
Geteilte Dateien der Diplomarbeit – Automatisiertes Rohrbiegesystem

## Aktueller Stand der Konstruktion (Stand: 2026-08-10)

### Biegekopf (in Arbeit)
Baugruppe `Mechanik/Biegekopf/BG001_..._biegekopf_gesamt_v1.iam`, aufgebaut auf dem Fairino FR20 Roboterarm.

- **Gehäuse** (`Mechanik/Biegekopf/Gehäuse/`): Getriebegehäuse, Motorgehäuse und Motordeckel (bereits in v2) konstruiert.
- **Antrieb**: Getriebe (`gearbox_ab115-100-s2-p2-12`) und Servomotor (Matsushita/Panasonic `MSMF082L1U1`) als Kaufteile eingebunden.
- **Biegewerkzeuge**: Biegerolle 62, Biegerolle 66, Hantelrolle und Bolzen als STEP-Teile vorhanden.
- **Verlängerung** (`Mechanik/Biegekopf/Verlängerung/`): eigene Baugruppe `BG002_..._verlängerung_gesamt_v1.iam` mit Aufnahme (BT007), Stab (BT008) und Bolzen (BT009).

### Biegelehre / Gesamtprojekt (abgeschlossen, Grundversion)
`Mechanik/Gesamtprojekt Biegelehre/`: Biegelehre-Gesamtbaugruppe inkl. Biegeaufsatz, Anschweißlasche und Einspannvorrichtung.

### Roboterarmauswahl
Fairino FR20 als Trägerarm ausgewählt und als CAD-Modell (`Mechanik/Fairino FR20/`) eingebunden.

### Elektronik (neu begonnen)
Erste Verkabelungsplanung in `Elektronik/Elektronik_Verkabelung_Rohrbiegesystem.drawio`.

### Offen / nächste Schritte
- Biegekopf-Konstruktion finalisieren (aktuell iterative Überarbeitung, siehe OldVersions-Stände)
- Elektronik/Verkabelung weiter ausarbeiten
- Fairino-Datenblatt (`Fairino_Daten.docx`) einarbeiten
