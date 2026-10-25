# Technisches Portfolio – Website Version 2

Dies ist eine lokal ausführbare Portfolio-Website mit HTML und CSS. Gegenüber Version 1 wurde nur der Ergebnisbereich des abgeschlossenen Referenzprojekts ergänzt. **Das Python-Framework selbst wurde nicht verändert.**

## Dateien

- `index.html` – Aufbau der Portfolio-Website
- `styles.css` – Gestaltung und responsive Darstellung
- `assets/plots/` – drei Diagramme, mit dem vorhandenen `create_plots.py` aus `test_run_001.csv` erzeugt
- `assets/test_report_preview.png` – gerenderte erste Seite des bereitgestellten PDF-Testberichts
- `assets/test_report.pdf` – unveränderte Kopie des Original-PDF-Berichts
- `assets/test_report.xlsx` – unveränderte Kopie des Original-Excel-Berichts

## Unter Windows mit VS Code öffnen

1. ZIP-Datei herunterladen und **Alle extrahieren** auswählen.
2. Den entpackten Ordner `portfolio-website-version-2` in VS Code über **Datei → Ordner öffnen** öffnen.
3. Im **Windows-Datei-Explorer** im entpackten Ordner `index.html` mit **Öffnen mit → Edge/Chrome** öffnen. Alternativ in VS Code per **Integrated Browser** anzeigen.
4. Auf der Website zum abgeschlossenen Projekt scrollen. Darunter stehen drei Diagramme und ein PDF-Vorschaubild.
5. Auf ein Diagramm klicken, um es groß zu sehen; auf **PDF-Bericht ansehen**, um den Bericht zu öffnen.
6. Spätere Änderungen an HTML/CSS in VS Code mit **Strg+S** speichern; im Browser mit **F5** aktualisieren.

Der Browser benötigt keine Python-Installation und keinen Webserver. Alle Dateien müssen im **gemeinsamen Ordner** bleiben, damit die Bilder und Berichte gefunden werden.

## Herkunft und Grenzen der dargestellten Ergebnisse

- Sämtliche Messungen des Referenzprojekts sind **simuliert**; es wurde kein realer Prüfstand verwendet.
- Der Beispiel-Testlauf `TR-001` enthält 500 Messdatensätze und drei absichtlich eingebaute Grenzwertverletzungen. Deshalb ist das Ergebnis 0 PASS / 3 FAIL **erwartet**, nicht ein Versagen des Test-Frameworks.
- Die Diagramme wurden mit dem vorhandenen Skript `create_plots.py` aus der bereitgestellten Datei `test_run_001.csv` erstellt; die Daten wurden nicht geändert.
- Die Berichte stammen unverändert aus den vom Nutzer bereitgestellten Projektdateien.
- Die weiteren Portfolio-Projekte bleiben ausdrücklich als **geplant** gekennzeichnet.
- Für die Veröffentlichung prüfen, ob die hochgeladenen Berichtsversionen veröffentlicht werden sollen. Die PDF-/Excel-Links zeigen derzeit lokale Kopien.
