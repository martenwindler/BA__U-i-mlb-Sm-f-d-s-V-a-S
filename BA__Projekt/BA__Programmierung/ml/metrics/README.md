```metrics_registry_definitions.py```:
Definiert umfangreiche Metrikfunktionen für Klassifikation, Regression und Unsicherheitsquantifizierung (inkl. ECE/ACE, NLL, ELBO, CRPS, UDA, NCG etc.) samt Hilfsroutinen zur Nutzung im `MetricsRegistry`-System.  

```metrics_registry.py```:
Stellt mit `MetricsRegistry` ein Singleton-Register bereit, um Metriken für Klassifikation, Regression und Unsicherheitsquantifizierung zu definieren, zu speichern, abzurufen und über Batches auszuwerten.

```metrics.py```:
Definiert die Klasse `Metric`, die Metrikfunktionen kapselt, deren Batch-Ergebnisse akkumuliert und zur Auswertung berechnet.  
