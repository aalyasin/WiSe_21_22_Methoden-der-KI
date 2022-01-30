### Warum ist KI wichtig?
Der Grundkonzept der KI ist über die Verarbeitung von einer großen Menge von Data, so groß dass Menschen nicht mehr arbeiten können. Da Maschine Speicherkapäzitat und Arbeitskraft viel größe als Mensch hat, lehrt man die Maschine zur Verarbeitung diese Datamenge, indem man ein Modell baut und in die Maschine implementiert.

### Was ist KI:
KI ist durch die Maschine die Verarbeitung von Data und damit die Antworte der Fragen. Breiter Begriff (Machine Learning) meint, dass Computer etwas gelernt haben. Enger Begriff meint, dass Computer Intelligenz vergleichbar mit den Menschen haben. Ganz enger Begriff meint Selbstbewussssein.

### Einsatz?
Das Periodensystem der KI von Bitkom, z.B. Computer Vision/Bilderkennung, Sprache geschrieben (Natural Language Processing), Sprache gesprochen (Speech Recognition), usw.

### Was wirklich ist Machine Learning:
ML bedeutet, dass Maschine die Algorithmen lernen, die auf Basis der Daten neue Algorithmen erstellen.
2 Algorithmen, oder 2 Phase:
- Training: Lernen, Modell erstellen
- Predicting: Modell auf neue Situation anwenden

### Was ist dann Modell?
Modell ist eine nützliche vereinfachte Repräsentation der Welt. Ein Machine Learning-Modell ist eine Datei, die darauf trainiert wurde, bestimmte Arten von Mustern zu erkennen. Sie trainieren ein Modell anhand von Daten, indem Sie einen Algorithmus bereitstellen, mit dem diese Daten analysiert und zum Lernen verwendet werden können.

### Definition von starke und swache KI:
- Starke (echte) KI: Die Algorithmen sind nicht „nachvollziehbar“ – können nicht manuell nachgeahmt werden. Die zu lösenden Probleme lassen sich nicht mathematisch exakt beschreiben (z.B.Personenerkennung, was Menschen nur intuitiv machen können und nicht explizit lernen) oder die mothemtische Komplexität ist prohibitiv (Spiele Schach, Go, Poker, etc)
- Schwache KI: Algorithmen können mit etwas Aufwand manuell benutzt werden

### 3 Typen von ML:
| Typen | Problem typ 1 | Problem typ 2 | Datentyp |
| - | - | - | - |
|Supervised (überwachtes)| Regression | Klassifikation | Labelled |
|Unsupervised (unüberwachtes)| Assoziation | Clustering | Unlabelled |
| Reinforcement (verstärkendes)| Predicting | Selbstbewusstsein | Ohne vorherdefiniert |

| Aufgabe | Erklärung | Prognose | Bemerkung |
| - | - | - | - |
| Klassification | Daten einer der zuvor definierten Kategorie zuordnen | Ja | Binär und Multiclass Klassification |
| Regression | Daten einem numerischen (kontinuierlichen) Wert zuordnen | Ja | - |
| Clustering | Kategorien festlegen und Daten einer dieser Kategorie zuordnen | Ja | Grundlage für Anomaly Detection |

### Feature:
Information in den Inputdaten sind bekannt als Fearture oder Merkmale.
| Kategorie | Beschreibung | Beispiele |
| - | - | - |
| Ordinal | Einzelne Werte mit Reihenfolge. Können numerisch oder nicht numerisch sein. | Schulnoten, Farben, Steuerklassen*, Buchstabe |
| Nominal | Einzelne Werte ohne Rangordnung und ohne Distanz | Geschlecht, Familienstand |
| Kardinal | Numerische Werte mit Reihenfolge und Abstandmetrik. Können ganze Zahlen oder Gleitkommazahlen sein. Oft mit einer Einheit (Grad, Meter, Kilogramm, Euro, etc.) | Alter, Entfernung, Geld, Zeit, Wochentage*, Anzahl |
| Besonder | Texte (mit und ohne Quellentext), Images,  Musik/Aufzeichnungen, Videos | - |

**One-hot-Kodierung für nominale Werte ist ein Vektor mit einer 1 und sonst nur 0

### Verlustfunktion:
- Abweichung von Zielzustand numerisch darstellen, damit wird bewertet, ob das Modell durch die Modifikation besser wird.
- Das Lernen ist ein Vorgang zum Training und zur Anpassung des Modells, um die Abweichung vom Ziel zu minimieren
- Bsp.: Für Regression ist die quadratische Entfernung.

### Binäre Klassifikation:
- Ein besonderes Typ von Klassifikation, wenn das Problem nur 2 Ergebnisse hat, m.a.W. das Modell 2 Ausgang hat.
- Auch eine Methode zur Bewertung eines Modells durch die Modifikation (Fitnessfunktion)
- In Tabellenform:

| - | echte Wahrheit | echte Falschheit |
| - | - | - |
| vorhergesagte Wahrheit (Positiv)| True Positiv | False Positiv |
| vorhergesagte Falschheit (Negativ)| False Negativ | True Negativ |

Je weniger Fälle in einer Kategorie, desto geringer die statistische Zuverlässigkeit.

### Overfitting/Überanpassung:
| Symptom | Beschreibung |
| - | - |
| 1 | Das Modell ist komplizierter als die Umstände hergeben, als 'angemessen' ist |
| 2 | Das Modell hat mehr Parameter als die Datenmenge hergibt |
| 3 | Unwichtige oder zufällige Details fließend ins Modell ein |
| 4 | Das Modell funktioniert gut oder 'zu gut' auf bestimmten Daten (trainierte Daten) aber viel schlechter auf neuen Daten |
| 5 | Das Modell hat bestimmte Situation 'aufwendig' gelernt, kann aber das Prinzip nicht begreifen|

**Probleme der Überanpassung: Eine präzise mathematische Definition fehlt, nur intuitive Sicht auf das Problem.

### Kreuzvalidierung:

Optimizer:

Was ist ...?

 Verlustfunktion:Abweichung von Zielzustand numerisch darstellen
  Lernen = Modell trainieren = Modell anpassen, um die Abweichung vom Ziel zu minimieren

 Optimierung:

 Überwachtes Lernen:

 Trainieren:

 Aktivierungsfunktion:

 Neuronales Netz:

 Regression: Daten einem numerischen ( Kontinuierlichen ) wert zuordnen.

 Klassifikation:
  Daten einer der zuvor definierten Kategorie zuordnen ( kann auch prognose sein ).
  
 Gewichte, Parameter und Hyperparameter

 Gradientenabstieg

 Lernrate:

 Genauigkeit, Bias:

 binäre Klassifikation: wie soll die Verlustfunktion gesteltet werden?
  was sind die wirtschaftlichen kosten und konsequenzen einer falschen klassifikation?
    -verdachtsfälle, die sich nicht bestätigen lassen
    -problemfälle, die nicht entdeckt wurden
  Im Einzelfaää sind die Konsequenzen sehr unterschiedlich (Eine Standartformel wird dem Einzelfall     nicht gerecht.
  Woche 3 seite 18

 Überanpassung(Overfitting):

 Regularisierung:

 Standardisierung:
