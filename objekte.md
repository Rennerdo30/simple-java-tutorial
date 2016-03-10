# Objekte

Objekte sind die wichtigste Grundlage einer objektorientierten Programmiersprache. Objekte sind Instanzen einer Klasse, daher Spricht man auch oft davon, dass eine Klasse ein Bauplan für ein Objekt darstellt. An dieser Stelle wäre eine kleine Metapher vielleicht angebracht:

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

Diese Art von Klasse würde man *"Bean"* nennen. Der Name kommt wohl von dem Ursprung der Namensgebung Javas. Java ist nach einer Insel benannt auf der Kaffee angebaut wird. Daher auch die Kaffeetasse im Logo. Eine "*Bean*", zu Deutsch Bohne, ist ja die Grundlage des Kaffees, somit ist diese wohl auch die Grundlage Javas. Eine "*Bean*" ist eine Klasse, welche nur für den Datenaustausch bzw. der Speicherung von Daten angelegt wurde. 
<br>
Wie Sie bestimmt schon bemerkt haben sind in dem Beispiel alle Variablen auf *"private"* gesetzt. Dies ist der Fall, da man in Java auf sogenannte *"getter-"* und *"setter-Methoden"* setzt. Durch den Einsatz dieser, ist es möglich die Daten vor dem eigentlichen abspeichern in der Variablen zu überprüfen. In den meisten IDEs ist es zwar möglich diese generieren zu lassen, Ich werde Ihnen dennoch ein Beispiel dazu zeigen:

```
public class Buch
{
  private String titel;
  private String autor;
  private String isbn;
  private String verlag;
  private int seitenZahl;
  
  //Setter-Methode für die Variable "titel"
  public void setTitel(String titel)
  {
    this.titel = titel;
  }
  
  //Setter-Methode für die Variable "autor"
  public void setAutor(String autor)
  {
    this.autor = autor;
  }
  
  //Setter-Methode für die Variable "isbn"
  public void setIsbn(String isbn)
  {
    this.isbn = isbn;
  }
  
  //Setter-Methode für die Variable "verlag"
  public void setVerlag(String verlag)
  {
    this.verlag = verlag;
  }
  
  //Setter-Methode für die Variable "seitenZahl"
  public void setSeitenZahl(int seitenZahl)
  {
    this.seitenZahl = seitenZahl;
  }
  
  //Getter-Methode für die Variable "titel"
  public String getTitel()
  {
    return this.titel;
  }
  
  //Getter-Methode für die Variable "autor"
  public String getAutor()
  {
    return this.autor;
  }
  
  //Getter-Methode für die Variable "isbn"
  public String getIsbn()
  {
    return this.isbn;
  }
  
  //Getter-Methode für die Variable "verlag"
  public String getVerlag()
  {
    return this.verlag;
  }
  
  //Getter-Methode für die Variable "seitenZahl"
  public int getSeitenZahl()
  {
    return this.seitenZahl;
  }
}

```

Ein Buch kann man lesen.

