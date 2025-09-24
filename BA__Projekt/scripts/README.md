`clean____pycache__.sh`:  
Das Skript wechselt ins Projektverzeichnis und löscht alle `__pycache__`-Ordner, wobei die Ausgabe optional mit `--quiet` unterdrückt werden kann.

`clean__all.sh`:  
Das Skript dient als Sammelroutine, die im Projektverzeichnis alle `clean__*.sh`-Skripte außer sich selbst ausführt und dabei optional mit `--quiet` die Ausgaben unterdrückt.

`clean__data-processed.sh`:  
Das Skript leert den Ordner `assets/data/processed/`, ohne ihn zu löschen, und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

`clean__doc.sh`:  
Das Skript löscht alle Inhalte im Ordner `assets/docs/`, behält den Ordner selbst bei und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

`clean__dotfiles.sh`:  
Das Skript entfernt alle `.DS_Store`-Dateien sowie Dateien mit Namenspräfix `._*` im Projektverzeichnis und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

`clean__egg-info.sh`:  
Das Skript löscht die Verzeichnisse `BA__Projekt.egg-info/` und `BA__Programmierung/BA__Projekt.egg-info` und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

`clean__logs.sh`:  
Das Skript löscht im angegebenen Log-Verzeichnis alle `persist__*.log`-Dateien bis auf die drei neuesten und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

`clean__ruffcache.sh`:  
Das Skript entfernt den Ordner `.ruff_cache/` mitsamt Inhalt und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

`clean__viz.sh`:  
Das Skript löscht alle Inhalte im Ordner `assets/viz/`, behält den Ordner selbst bei und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```clean__zone-identifier.sh```:
Das Skript entfernt alle Dateien mit der Endung `Zone.Identifier` im Projektverzeichnis und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```clean--dbs.sh```:
Das Skript löscht alle Inhalte im Ordner `assets/dbs/`, behält den Ordner selbst bei und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```clean--tests.sh```:
Das Skript löscht alle Inhalte im Ordner `tests/`, behält den Ordner selbst bei und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```create__doc.sh```:
Das Skript erstellt mit Sphinx automatisch die Projektdokumentation, indem es eine Grundkonfiguration anlegt, `.rst`-Dateien generiert und die HTML-Dokumentation baut, wobei optional mit `--quiet` Ausgaben unterdrückt werden können.

```create__files_by_token.sh```:
Das Skript erzeugt in einem Zielordner neue Dateien mit angegebenem Präfix und Dateiendung, indem es Tokens aus piped Input extrahiert und diese im Dateinamen verwendet, wobei optional mit `--quiet` Ausgaben unterdrückt werden können.

```create__files_dataset_training_viz_by_token.sh```:
Das Skript erstellt interaktiv neue Dataset-, Modell- und Testdateien mit einem gemeinsamen Token im Dateinamen, legt dafür die benötigten Verzeichnisse an und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```data_source__all.sh```:
Das Skript führt in festgelegter Reihenfolge mehrere `data-source__*.sh`-Skripte zur Datenaufbereitung aus und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```data_source__extract-archives.sh```:
Das Skript entpackt im Quellordner ZIP- und TAR.GZ-Archive, verschiebt CSV- und ARFF-Dateien jeweils in eigene Unterordner und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```data_source__flatten.sh```:
Das Skript flacht rekursiv alle Unterordner in `assets/data/raw/` ab, verschiebt Dateien nach oben und löst Namenskonflikte durch Umbenennung, wobei optional mit `--quiet` die Ausgaben unterdrückt werden können.

```data_source__move.sh```:
Das Skript verschiebt alle Unterverzeichnisse aus `assets/data/source/` nach `assets/data/raw/`, ersetzt bestehende Zielordner bei Bedarf und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```data_source__rename.sh```:
Das Skript benennt alle Dateien im Ordner `assets/data/source/` so um, dass sie mit `dataset__` beginnen, ersetzt dabei Pluszeichen durch Unterstriche und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```data-source__convert.sh```:
Das Skript konvertiert Datensätze in `assets/data/raw/` mithilfe externer Python-Skripte von Excel-, ARFF- und TXT-Dateien nach CSV und gibt optional Statusmeldungen aus, sofern kein `--quiet`-Flag gesetzt ist.

```data-source__rename-csv.sh```:
Das Skript überprüft die benötigten Python-Abhängigkeiten und konvertiert in `assets/data/raw/` enthaltene Excel-, ARFF- und TXT-Dateien mithilfe externer Konverter-Skripte in CSV-Dateien, wobei optional mit `--quiet` die Ausgaben unterdrückt werden können.

```print__folder_contents_by_depth.sh```:
Das Skript gibt die Inhalte eines Zielordners als Baumstruktur aus und erlaubt optional die Begrenzung der Verschachtelungstiefe.

```service__restart_all.sh```:
Das Skript beendet einen laufenden TensorBoard-Prozess, indem es dessen PID ermittelt und den Prozess killt, oder gibt aus, dass kein Prozess läuft.  

```test__all.sh```:
Das Skript führt mit Python `unittest discover` alle Testdateien im Verzeichnis `tests/` aus und bricht bei Fehlern sofort ab.  