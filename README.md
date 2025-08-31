# Reproduzierbarkeit der Bachelorarbeit  
**Titel:** Verbindungslinien zwischen Astrologie, Achtsamkeit, Medizinskepsis und CAM  

Dieses Repository enthält die Daten und den Code, die im Rahmen der Bachelorarbeit *„Verbindungslinien zwischen Astrologie, Achtsamkeit, Medizinskepsis und CAM“* verwendet wurden.  
Ziel ist es, die Reproduzierbarkeit der durchgeführten Kanonischen Korrelationsanalyse (KKA) sicherzustellen.  

---

## Ordnerstruktur

- **data/raw/**  
  Enthält die Rohdaten der Befragung:  
  - `Daten_Fragebogen_aktuell.csv` – anonymisierte Umfragedaten  

- **code/**  
  Enthält alle Skripte zur Datenaufbereitung, Modellierung und Analyse:  
  - `00_run_all.R` – Master-Skript, das die gesamte Analysepipeline ausführt  
  - `01_setup_and_cleaning.R` – Datenaufbereitung und Bereinigung der Rohdaten  
  - `02_cca_models.R` – Durchführung der Kanonischen Korrelationsanalyse  
  - `CCA sets 2.Rmd` – Dokumentation und erste Exploration der Variablensets  
  - `cca.Rmd` – Hauptskript für Analyse, Abbildungen und Ergebnisdarstellung  

- **CODEBOOK.csv**  
  Übersicht und Beschreibung der verwendeten Variablen.  

- **CITATION.cff**  
  Zitationsinformationen zum Repository.  

- **LICENSE**  
  Lizenzdatei zur Nutzung und Weitergabe.  

- **README.md**  
  Einführung und Hinweise zur Verwendung des Repositories.  

---

## Reproduzierbarkeit

Die Ergebnisse der Arbeit lassen sich reproduzieren, indem das Skript **`00_run_all.R`** ausgeführt wird.  
Dieses Skript lädt die Rohdaten, bereitet sie auf, führt die KKA durch und erstellt die relevanten Abbildungen.  

---

## Lizenz & Zitation

Bitte beachten Sie die Angaben in der Datei **LICENSE** sowie die Zitationsinformationen in **CITATION.cff**.  
