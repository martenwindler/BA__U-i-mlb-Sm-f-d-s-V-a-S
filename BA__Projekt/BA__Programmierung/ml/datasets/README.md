```dataset__torch__base_image_classification.py```:
Implementiert ein generisches PyTorch-Dataset für Bildklassifikation aus CSV-Dateien mit Label- und Pixelspalten, inklusive optionaler Normalisierung und Transformation. 

```dataset__torch__base_tabular.py```:
Stellt eine generische PyTorch-Dataset-Klasse für Tabellendaten bereit, mit optionaler Normalisierung für Features und Targets sowie Unterstützung für Klassifikation und Regression. 

```dataset__torch__boston_housing.py```:
Definiert ein PyTorch-Dataset für das Boston Housing Dataset, lädt die CSV-Datei, benennt Spalten und nutzt `BaseTabularDataset` mit Normalisierung. 

```dataset__torch__cifar_10_python.py```:
Implementiert ein PyTorch-Dataset für CIFAR-10, das die mit Python-Pickles gespeicherten Batch-Dateien lädt, Bilder normalisiert und Labels bereitstellt. 

```dataset__torch__combined_cycle_power_plant.py```:
PyTorch-Dataset für das Combined Cycle Power Plant, das CSV-Daten lädt, Normalisierung unterstützt und Features ["AT","V","AP","RH"] mit Ziel "PE" bereitstellt. 

```dataset__torch__concrete_compressive_strength.py```:
PyTorch-Dataset für das Concrete Compressive Strength, das CSV-Daten lädt, Spalten bereinigt, Normalisierung unterstützt und Features von der Zielspalte trennt. 

```dataset__torch__condition_based_maintenance_of_naval_propulsion_plants.py```:
PyTorch-Dataset für das Naval Propulsion Plants, das spaltenlose CSVs lädt, 18 Spalten validiert, Spalten in Strings umwandelt und Normalisierung unterstützt. 

```dataset__torch__duckdb_iris.py```:
PyTorch-Dataset für das Iris-Set, das Daten aus einer DuckDB-Tabelle lädt, Spalten umbenennt, Spezies in numerische Klassenlabels mappt und für Klassifikation aufbereitet. 

```dataset__torch__energy_efficiency.py```:
PyTorch-Dataset für den Energy-Efficiency-Datensatz, das CSV-Daten lädt, fehlende Werte entfernt, ein Zielattribut wählt und optionale Normalisierung unterstützt. 

```dataset__torch__fmnist.py```:
Stellt eine Ladefunktion für Fashion-MNIST bereit, die Trainings- und Testdatensätze aus CSV-Dateien als PyTorch-Datasets zurückgibt. 

```dataset__torch__kin8nm.py```:
Lädt das Kin8nm-Datenset aus einer CSV-Datei als normalisiertes PyTorch-Tabellendataset. 

```dataset__torch__kmnist.py```:
Lädt die KMNIST-Trainings- und Testdatensätze aus CSV-Dateien als normalisierte PyTorch-Bildklassifikationsdatasets. 

```dataset__torch__mnist.py```:
Lädt die MNIST-Trainings- und Testdatensätze aus CSV-Dateien als normalisierte PyTorch-Bildklassifikationsdatasets. 

```dataset__torch__nmavani_func1.py```:
Definiert ein PyTorch-Dataset für tabellarische Daten zur Beispiel Funktion abgesprochen mit Ninad aus einer DuckDB-Tabelle mit optionaler Normalisierung. 

```dataset__torch__wine_quality_red.py```:
Definiert ein PyTorch-Dataset für den Red-Wine-Quality-Datensatz aus CSV mit semikolongetrennten Spalten ohne Normalisierung. 

```dataset__torch__wine_quality_white.py```:
Definiert ein PyTorch-Dataset für den White-Wine-Quality-Datensatz aus CSV mit semikolongetrennten Spalten ohne Normalisierung. 