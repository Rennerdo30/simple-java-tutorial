# Deklaration und Initialisierung einer Variablen

##Deklaration
In Java sieht eine solche Deklaration wie folgt aus:

```<Zugriffsmodifizierer> <Typ> <Name>;```

Ein Beispiel:
Wir wollen eine ganze-Zahl in einer Variablen abspeichern. Diese Zahl ist das Alter einer Person.

```
//<Typ> = int
//<Name> = personAlter
int personAlter;
```

Wie Sie sehen können ist in dem Beispiel kein Zugriffsmodifizierer enthalten. Dieser ist nicht nötig und ist, wie der Name schon sagt nur dafür da, die Berechtigung für den Zugriff auf eine Variable zu verändern.

Ein Beispiel mit Zugriffsmodifizierer wäre:

```
//<Zugriffsmodifizierer> = public
//<Typ> = int
//<Name> = personAlter
public int personAlter;
```

##Initialisierung

In Java werden Variablen initialisiert, indem Ihnen ein Wert zugewiesen wird. Der zugewiesene Wert, muss jedoch mit dem Typ der Variablen übereinstimmen/kompatibel sein. Allgemein lässt sich die Initialisierung in zwei Kategorien einteilen:

* **Initialisierung Primitiver Datentypen:**
<br>
Primitive Datentypen werden einfach durch Zuweisung eines dem Typs der Variablen entsprechenden Wertes initialisiert. Dies könnte dies wie folgt aussehen:

```
    int kundenNummer = 123456789;
    char kategorie = 'c';
    float preis = 17.99F;
```
 
 Es gibt jedoch eine **Ausnahme**!
 Der Datentyp *"String"* ist zwar kein Primitiver Datentyp, kann aber wie ein solcher initialisiert werden!
 
```
    String vorname = "Peter";
```

 

* **Initialisierung von Objekten:**
