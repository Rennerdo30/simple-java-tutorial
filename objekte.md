# Objekte

Objekte sind die wichtigste Grundlage einer Objektorientierten Programmiersprache. Objekte sind Instanzen einer Klasse, daher Spricht man auch oft davon, dass eine Klasse ein Bauplan für ein Objekt ist. An dieser Stelle wäre eine kleine Metapher vielleicht angebracht:

Stellen sie sich vor, das sie eine Vorlage haben, auf der genau erklärt ist was ein Buch ist und was ein solches Ausmacht (Attribute, Eigenschaften, Funktionen,...). 
Ein Buch hat einen Autor, einen Titel, eine ISBN, einen Verlag, eine bestimmte Anzahl an Seiten und vieles mehr. Das wären unsere Attribute der Klasse *"Buch"*

In Java könnte man diese Klasse *"Buch"* etwas so aussehen lassen:

```
public class Buch
{
  private String titel;
  private String autor;
  private String isbn;
  private String verlag;
  private int seitenZahl;
}
```

Diese Art von Klasse würde man *"Bean"* nennen. Der Name kommt wohl von dem Ursprung der Namensgebung Javas. Java ist nach einer Insel benannt auf der Kaffee angebaut wird. Daher auch die Kaffeetasse im Logo. Eine "*Bean*", also zu deutsch Bohne, ist ja die Grundlage des Kaffees, somit ist diese Auch die Grundlage Javas. Eine "*Bean*" ist eine Klasse, welche nur für den Datenaustausch bzw. der Speicherung von Daten angelegt wurde. 
Wie Sie bestimmt schon bemerkt haben sind in dem Beispiel alle Variablen auf *"private"* gesetzt. Dies ist der Fall, da man in Java auf so genannte *"getter-"* und *"setter-Methoden"* setzt. Durch den Einsatzt dieser, ist es möglich die Daten vor dem eigendlichen abspeichern in der Variablen zu überprüfen. In den meisten IDEs ist es zwar möglich diese generieren zu lassen. Ich werde Ihnen dennoch ein Beispiel dazu zeigen:

```
public class Buch
{
  private String titel;
  private String autor;
  private String isbn;
  private String verlag;
  private int seitenZahl;
  
  //Dies ist eine setter-Methode für die Variable "titel".
  public void setTitel(String titel)
  {
    this.titel = titel;
  }
  
   public void setAutor(String autor)
  {
    this.autor = autor;
  }
   public void setIsbn(String isbn)
  {
    this.isbn = isbn;
  }
    public void setVerlag(String verlag)
  {
    this.verlag = verlag;
  }
}

```

Ein Buch kann man lesen, es vieleicht als 

