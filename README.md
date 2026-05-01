# Process Time Series Analysis Basics

This repository contains introductory teaching materials for process time-series analysis with Python and Jupyter Notebooks. The materials focus on data quality, interpolation, exploratory time-series analysis, spectral analysis, filtering, resampling, and decomposition methods for technical and process-related time series.

The notebooks are designed as teaching and self-study material for applied AI, process automation, data science, and predictive maintenance. The focus is on understanding time-series behavior and preparing data for later monitoring or machine-learning workflows.

## Target audience

The material is intended for students in process automation, applied AI, data science, and predictive maintenance.

## Contents

The repository covers:

- interpolation and missing values,
- time index and sampling,
- noise, peaks, and moving averages,
- periodogram and Welch PSD,
- low-pass filtering,
- resampling,
- STL and MSTL,
- TCLab-related examples,
- real-data analysis with the UCI Household Electric Power Consumption dataset.

## Data and external sources

The repository uses or refers to the following external sources:

- APMonitor / Data Science with the TCLab: https://github.com/APMonitor/data_science
- UCI Household Electric Power Consumption dataset: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

The APMonitor-based parts mainly concern the TCLab-related notebooks on interpolation and time-series analysis. The UCI dataset is used as an example of a real, noisy technical time series for data quality checks, spectral analysis, filtering, resampling, STL, and MSTL.

## Authorship and AI assistance

This repository was created and curated by Thomas Eichhorn for teaching process time-series analysis in the context of process automation and applied AI.

Parts of the material were developed with support from ChatGPT (GPT-5.5). All AI-assisted content was reviewed, adapted, and integrated by Thomas Eichhorn.

## License and third-party material

The original content of this repository is licensed under the MIT License.

See [LICENSE](LICENSE) for details.

This repository also contains adapted teaching material based on the APMonitor Data Science notebooks:

- https://github.com/APMonitor/data_science

The APMonitor-based parts mainly concern the TCLab-related notebooks on interpolation and time-series analysis:

- `Notebook 01 - TCLab 09. Interpolation.ipynb`
- `Notebook 02 - TCLab 12. Zeitreihen.ipynb`

The APMonitor materials were adapted and extended for this repository. The main changes include:

- translation and language adaptation into German,
- didactic revision for process automation,
- corrections,
- new Markdown explanations.

The original APMonitor materials are licensed under the MIT License. Third-party notices and the original APMonitor license text are documented in:

- [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)

All other notebooks in this repository are original teaching materials created by Thomas Eichhorn with support from ChatGPT.

# Grundlagen der Prozesszeitreihenanalyse

Dieses Repository enthält einführende Lehrmaterialien zur Analyse von Prozesszeitreihen mit Python und Jupyter Notebooks. Im Mittelpunkt stehen Datenqualität, Interpolation, explorative Zeitreihenanalyse, Spektralanalyse, Filterung, Resampling und Zerlegungsverfahren für technische und prozessbezogene Zeitreihen.

Die Notebooks sind als Lehr- und Selbstlernmaterial für angewandte KI, Prozessautomation, Data Science und Predictive Maintenance konzipiert. Der Fokus liegt auf dem Verständnis von Zeitreihenverhalten und der Vorbereitung von Daten für spätere Monitoring- oder Machine-Learning-Workflows.

## Zielgruppe

Das Material richtet sich an Studierende in Prozessautomation, angewandter KI, Data Science und Predictive Maintenance.

## Inhalte

Das Repository behandelt:

- Interpolation und fehlende Werte,
- Zeitindex und Abtastung,
- Rauschen, Peaks und gleitende Mittelwerte,
- Periodogramm und Welch-PSD,
- Tiefpassfilterung,
- Resampling,
- STL und MSTL,
- TCLab-nahe Beispiele,
- Realdatenanalyse mit dem UCI Household Electric Power Consumption Datensatz.

## Daten und externe Quellen

Das Repository nutzt oder verweist auf folgende externe Quellen:

- APMonitor / Data Science with the TCLab: https://github.com/APMonitor/data_science
- UCI Household Electric Power Consumption Datensatz: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

Die APMonitor-basierten Teile betreffen vor allem die TCLab-bezogenen Notebooks zu Interpolation und Zeitreihenanalyse. Der UCI-Datensatz wird als Beispiel für eine reale, verrauschte technische Zeitreihe zur Prüfung von Datenqualität, Spektralanalyse, Filterung, Resampling, STL und MSTL verwendet.

## Autorenschaft und KI-Unterstützung

Dieses Repository wurde von Thomas Eichhorn für die Lehre zur Analyse von Prozesszeitreihen im Kontext von Prozessautomation und angewandter KI erstellt und kuratiert.

Teile des Materials wurden mit Unterstützung von ChatGPT (GPT-5.5) entwickelt. Alle KI-unterstützten Inhalte wurden von Thomas Eichhorn geprüft, angepasst und in das Lehrmaterial integriert.

## Lizenz und Drittmaterial

Die eigenen Inhalte dieses Repositories stehen unter der MIT-Lizenz.

Details siehe [LICENSE](LICENSE).

Dieses Repository enthält außerdem bearbeitetes Lehrmaterial auf Basis der APMonitor Data Science Notebooks:

- https://github.com/APMonitor/data_science

Die APMonitor-basierten Teile betreffen vor allem die TCLab-bezogenen Notebooks zu Interpolation und Zeitreihenanalyse:

- `Notebook 01 - TCLab 09. Interpolation.ipynb`
- `Notebook 02 - TCLab 12. Zeitreihen.ipynb`

Die APMonitor-Materialien wurden für dieses Repository angepasst und erweitert. Die wichtigsten Änderungen umfassen:

- Übersetzung und sprachliche Anpassung ins Deutsche,
- didaktische Überarbeitung für die Prozessautomation,
- Korrekturen,
- neue Markdown-Erklärungen.

Die originalen APMonitor-Materialien stehen unter der MIT-Lizenz. Die Third-Party-Hinweise und der originale APMonitor-Lizenztext sind dokumentiert in:

- [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)

Alle weiteren Notebooks in diesem Repository sind eigene Lehrmaterialien von Thomas Eichhorn, erstellt mit Unterstützung von ChatGPT.
