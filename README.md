# Beschreibung

Schreiben Sie eine Klasse für einen binären Suchbaum. Ein binärer Suchbaum ist eine Graph, in dem Daten sortiert gespeichert werden. Ausgehend von einer Wurzelknoten (*root*), hat jeder Knoten im Graph zwei Kindknoten: ein "linkes Kind" und ein "rechtes Kind".  Die Kinder können ebenfalls wieder Kinder haben, etc. Den linken, bzw. rechten Knoten und alle Kinder nennt man linken, bzw. rechten Teilbaum. 

Jeder Knoten beinhaltet den ein Element des Suchbaums, zum Beispiel eine Zahl. Die Elemente aller Knoten im Linken Teilbaum sind kleiner als das Element des aktuellen Knotens, im rechten sind sie größer. Jedes Element kann maximal einmal vorkommen. Hier ist ein Beispiel für einen kleinen Suchbaum.

```
     5
    / \
   3   8
  / \
 1   4
```

Diese Aufgabe ist deutlich komplexer als die bisherigen Aufgaben und unterteilt sich daher in mehrere Teilaufgaben. 

## Grundgerüst

Erstellen Sie das Grundgerüst für die Klasse des Suchbaums. Der Baum soll die folgenden Methoden unterstützen:
- Hinzufügen einzelner Elemente
- Entfernen einzelner Elemente
- Ausgabe als String
- Hinzufügen aller Elemente eines Sequenztyps (z.B. Liste, Menge)
- Entfernen aller Elemente eines Sequenztyps (z.B. Liste, Menge)
- (Lesbare) Ausgabe des Baums als Zeichenkette (pretty print)
- Rückgabe aller Elemente des Baums als sortierte Liste

Sie müssen nicht zwingend von beliebigen Objekten als Element ausgehen. Sie können annehmen, dass es sich um Zahlen handelt.

## Implementation

Implementieren Sie alle Methoden des Grundgerüsts.

## Dokumentation

Erstellen Sie ein API Dokumentation (e.g. Javadoc, Doxygen, docstrings, ...) für alle Methoden und die Klasse selbst.
