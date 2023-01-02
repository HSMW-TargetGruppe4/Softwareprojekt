# Softwareprojekt

Willkommen auf der GitHub-Page für das Softwareprojekt forensische Werkzeuge (hate speech &amp; target) der TargetGruppe_4!

## Tasks
### Teilaufgabe a: Hate-Speech-Detektion

Trainieren Sie mit Hilfe des Entwicklungsdatensatzes einen Klassifikator, der für Twitternachrichten entscheiden kann, ob eine Nachricht Hate Speech beinhaltet oder nicht. Evaluieren Sie Ihren Klassifikator mit Hilfe der k-fold Crossvalidation. Dieses Ergebnis ist Grundlage Ihres Systempapers. Ende November erhalten Sie einen ungelabelten Testdatensatz. Nutzen Sie Ihr bestes System, um Vorhersagen, in der unter Abgabe beschriebenen Form, zu erzeugen und zur Evaluation einzureichen.


### Teilaufgabe b: Target-Detektion

Trainieren Sie mit Hilfe des Entwicklungsdatensatzes einen Klassifikator, der für Twitternachrichten entscheiden kann, ob eine Nachricht ungerichtet ist, oder sich an eine Gruppe oder Einzelperson richtet. Evaluieren Sie Ihren Klassifikator mit Hilfe der k-fold Crossvalidation. Dieses Ergebnis ist ebenfalls Grundlage Ihres Systempapers. Ende November erhalten Sie einen ungelabelten Testdatensatz. Nutzen Sie Ihr bestes System, um Vorhersagen, in der unter Abgabe beschriebenen Form, zu erzeugen und zur Evaluation einzureichen.

## Datensätze

Additional datasets were used to balance the datasets and to improve the accuracy of the classification. The datasets were adjusted to the given development dataset. The following datasets were used:

GERMEVAL 2018
For this corpus, to balance the label distribution for hate speech, 5,008 datasets labelled as ‘OFFENSE’ were added to the development dataset under formatting as binary ‘hate speech’ label.

GERMEVAL 2019
For this corpus, records labelled as ‘OFFENSE’ for hate speech. 1,957 records were added to the development dataset under formatting as a binary ‘hate speech’ label to balance the label distribution.

HASOC 2019
For this corpus, to balance the label distribution for hate speech, 407 records labelled as ‘HOF’ and 3,412 labelled as ‘NOT’ were added to the development dataset under formatting as a binary ‘hate speech’ label.

Toxic Comments corpus
First, the Toxic Comments corpus was restricted to only those records labelled as ‘Toxic’. These 13,458 records were then translated from the original (English) into German. In order to balance the label distribution for hate speech, labelled records were added to the development dataset and formatted as a binary ‘hate speech’ label.

By taking the balancing of the dataset into account, 32,374 data records are passed to the classification process in the training. That's an increase of four times the original development dataset containing only 8,132 sets.

## Ergebnisse
### Hate speech Klassifikator

The best performing model, both in the hate speech and non-hate speech classification, is the SVM with a f1-score of 0.859 (hate speech) and 0.838 (non-hate speech), as well as an overall cross-validation score of 85.29 %.

### Target entities Klassifikator

The best performing model overall (regarding cross-validation score) is RandomForestClassifier with a cross-validation score of 76.0%.

### Classification Reports

Die Einzelperformances der Klassifikatoren ist in einer jeweiligen Klassifikationszusammenfassung unter https://github.com/HSMW-TargetGruppe4/Softwareprojekt/tree/main/classification%20results dargestellt. 
