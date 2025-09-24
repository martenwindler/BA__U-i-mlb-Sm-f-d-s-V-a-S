```/conv/```:
Der Ordner enhtält alle Skripte zum Konvertieren von Daten.

```/db/```:
Der Ordner enthält alle Skripte zum Persistieren von Daten.

```/gen/```:
Der Ordner enthält alle Skripte zum Generieren von Daten. 

```/ml/```:
Der Ordner enthält alle machine-learning verwandte Skripte.

```/util/```:
Der Ordner enthält Skripte mit Pattern zur Vereinfachung (zur Zeit nur Singleton).

```/viz/```:
Der Ordner enthält alle Skripte zur Visualisierung.

```config.py```:
Das Modul definiert zentrale Projektpfade und Dateikonstanten für Daten, Modelle, Logs, Skripte, Tests und Visualisierungen.  

```main.py```:
Das Skript hält die Hauptroutine des Projekts. Ein For-Loop iteriert String-Token aus einer Liste, die einem Datensatz entsprechen wie 'boston-housing'. Initialisiert eine Datenbank, verfügbare Trainingsskripte für Evidential-Regression, und Visualisierung und überspringt ausgewählte Datensätze einer 'Token-Ignorier-Liste'.  
