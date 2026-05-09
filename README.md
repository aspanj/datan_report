# Data Analysis Report (datan_report)

## 📌 Projektübersicht
Dieses Repository enthält einen reproduzierbaren Datenanalyse-Bericht. Die Pipeline nutzt **R** für die methodische Datenaufbereitung und Modellierung sowie **Quarto**, um die analytischen Ergebnisse nahtlos in publikationsreife Formate (HTML und PDF) zu überführen. 

Ziel dieses Projekts ist es, transparente, gut dokumentierte und programmatisch generierte Insights bereitzustellen.

## 📂 Projektstruktur
Die Architektur des Repositories ist auf eine saubere Trennung von Code, Visualisierungen und finalen Reports ausgelegt:

```text
datan_report/
├── datan_report.Rproj    # RStudio Projektdatei für das Umgebungsmanagement
├── datan_report.qmd      # Quarto Markdown (Haupt-Analysedokument mit R-Code)
├── _quarto.yml           # Quarto-Konfigurationsdatei (Metadaten & Output-Settings)
├── datan_report.html     # Kompilierter Bericht (Interaktives Webformat)
├── datan_report.pdf      # Kompilierter Bericht (Statisches Printformat)
├── figures/              # Generierte Diagramme und Plots der Analyse
├── images/               # Statische Bilder und externe Grafiken
└── .gitignore            # Ignorierte temporäre Dateien und System-Caches
