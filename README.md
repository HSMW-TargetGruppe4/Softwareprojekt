# Softwareprojekt
Softwareprojekt forensische Werkzeuge (hate speech &amp; target)

Willkommen auf der GitHub-Page

## Tasks
### Teilaufgabe a: Hate-Speech-Detektion

Trainieren Sie mit Hilfe des Entwicklungsdatensatzes einen Klassifikator, der für Twitternachrichten entscheiden kann, ob eine Nachricht Hate Speech beinhaltet oder nicht. Evaluieren Sie Ihren Klassifikator mit Hilfe der k-fold Crossvalidation. Dieses Ergebnis ist Grundlage Ihres Systempapers. Ende November erhalten Sie einen ungelabelten Testdatensatz. Nutzen Sie Ihr bestes System, um Vorhersagen, in der unter Abgabe beschriebenen Form, zu erzeugen und zur Evaluation einzureichen.


### Teilaufgabe b: Target-Detektion

Trainieren Sie mit Hilfe des Entwicklungsdatensatzes einen Klassifikator, der für Twitternachrichten entscheiden kann, ob eine Nachricht ungerichtet ist, oder sich an eine Gruppe oder Einzelperson richtet. Evaluieren Sie Ihren Klassifikator mit Hilfe der k-fold Crossvalidation. Dieses Ergebnis ist ebenfalls Grundlage Ihres Systempapers. Ende November erhalten Sie einen ungelabelten Testdatensatz. Nutzen Sie Ihr bestes System, um Vorhersagen, in der unter Abgabe beschriebenen Form, zu erzeugen und zur Evaluation einzureichen.

## Ergebnisse
### Hate speech Klassifikator

The best performing model, both in the hate speech and non-hate speech classification, is the SVM with a f1-score of 0.859 (hate speech) and 0.838 (non-hate speech), as well as an overall cross-validation score of 85.29 %.

### Target entities Klassifikator

The best performing model overall (regarding cross-validation score) is RandomForestClassifier with a cross-validation score of 76.0%.
