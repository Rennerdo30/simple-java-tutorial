# Variablen

Variablen sind eines der Wichtigsten Elemente der Programmierung. Ohne sie wäre kaum etwas möglich.
Die Deklaration einer Variablen in Java zählt zu den einfachsten Dingen überhaupt. In Java sieht eine solche Deklaration wie folgt aus:

```<Zugriffsmodifizierer> <Typ> <Name>;```

Ein Beispiel:
Wir wollen eine Ganze-Zahl in einer Variablen abspeichern. Diese Zahl ist das Alter einer Person.

```
//<Typ> = int
//<Name> = personAlter
int personAlter;
```

Wie sie sehen können ist in dem Beispiel kein Zugriffsmodifizierer enthalten. Dieser ist nicht nötig und ist wie der Name schon sagt nur dafür da die Berechtigung für den Zugriff auf eine Variable zu verändern.

Ein Beispiel mit Zugriffsmodifizierer wäre:

```
//<Zugriffsmodifizierer> = public
//<Typ> = int
//<Name> = personAlter
public int personAlter;
```
