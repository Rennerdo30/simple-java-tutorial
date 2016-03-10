# Die Main-Methode

Die Main-Methode, ist jene Methode einer Klasse, die bei dem Programmstart ausgeführt wird. Es kann in einer Klasse immer nur eine Main-Methode geben, jedoch kann es in einem Projekt mehrere Klassen geben, welche eine Main-Methode enthalten. Bei dem Start des Java-Programms muss immer der "Pfad" zu der Klasse, die die Main-Methode enthält angegeben werden.

Eine Klassen mit einer Main-Methode könnte wie folgt aussehen:

```
//Klassen-Deklaration
public class MainBeispiel
{
  
  //Deklaration der Main-Methode
  public static void main(String[] args)
  {
    //Hier kommt der Code rein, der bei dem Programmstart ausgeführt werden soll
  }
  
}
```
Der Grund-Layout der Main-Methode ist immer gleich und kann nicht abgeändert werden! Nur der Name der Variablen "args" kann beliebig gewählt werden.