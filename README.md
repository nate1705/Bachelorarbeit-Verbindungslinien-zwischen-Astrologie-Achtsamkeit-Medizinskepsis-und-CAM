# Reproduzierbarkeit der Analysen zur Bachelorarbeit  
**Titel der Arbeit:** *Verbindungslinien zwischen Astrologie, Achtsamkeit, Medizinskepsis und CAM*  
**Autor:** [Dein Name]  

Dieses Repository enthält die Daten, den Programmiercode und die Abbildungen, wie sie in der Bachelorarbeit verwendet wurden. Damit können sämtliche Analysen und Darstellungen reproduziert werden.  

Zur Replikation wird lediglich eine aktuelle R-Version (> 4.0) benötigt sowie die im Code angegebenen R-Pakete. Eine detaillierte Anleitung zur Installation und Reproduktion ist in der Datei `README_reproduce.md` enthalten.  

---

## Struktur des Repositories

### Ordner **Data**
- Die Datei `Daten_Fragebogen_aktuell.csv` enthält die anonymisierten Befragungsdaten, die für die Analysen genutzt wurden.  
- Die Daten sind so aufbereitet, dass alle Ergebnisse bei Ausführung des Codes reproduziert werden können.  

---

### Ordner **Figures**
- Enthält alle in der Arbeit verwendeten Abbildungen, die durch die Analyse-Skripte generiert wurden.  
- Abbildungen sind nach Analyseabschnitten geordnet und entsprechen exakt den in der Bachelorarbeit dargestellten Grafiken.  

---

### Ordner **R Scripts**
- `main_analysis.Rmd`: Zentrales Skript für die Durchführung der Kanonischen Korrelationsanalyse und die Erstellung der in der Arbeit gezeigten Ergebnisse.  
- Alle weiteren Hilfsskripte (z. B. für Datenbereinigung, grafische Darstellung) sind hier abgelegt.  
- Die Skripte sind so strukturiert, dass bei Vorliegen der Daten mit einem einzigen Lauf (`Knit to HTML/PDF`) die gesamten Ergebnisse reproduziert werden können.  

---

## Reproduktion der Ergebnisse
1. Repository herunterladen oder klonen.  
2. Sicherstellen, dass R und RStudio installiert sind.  
3. Die im Skript angegebenen R-Pakete installieren.  
4. `main_analysis.Rmd` ausführen.  
   - Die Abbildungen werden automatisch im Ordner `Figures` gespeichert.  
   - Die Ergebnisse entsprechen den in der Arbeit berichteten Werten.  

---

## Hinweis zur Transparenz
Die Daten wurden anonymisiert und enthalten keine personenbezogenen Informationen. Repository und Daten stehen für die wissenschaftliche Nachnutzung im Sinne guter wissenschaftlicher Praxis zur Verfügung.  

---

## Kontakt
Bei Fragen oder Problemen zur Reproduktion wenden Sie sich bitte an:  
[Deine E-Mail-Adresse]  
