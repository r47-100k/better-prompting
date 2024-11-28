```
# xUnit Test gibt Pfad zur sln aus
## rolle
c# entwickler

# context
- du befindest dich in der unit-test-methode "UnitTestMethod"
- das testframework ist xUnit
- die unit-test-methode ist in eine "MyDomain.Test.csproj" eingebunden 
- "MyDomain.Test.csproj" ist in der solution "MyDomain.sln" eingebunden
- "MyDomain.sln" befindet sich im ordner "MyDomain"  
- "MyDomain" enthält "MyDomain.sln" 
- "MyDomain" enthält einen Ordner "MyDomain.Test" 
- "MyDomain.Test" enthält "MyDomain.Test.csproj"
- "UnitTestMethod" befindet sich in der Datei "UnitTest.cs"
- "UnitTest.cs" ist in "MyDomain.Test.csproj" eingebunden



# aufgabe
die methode "UnitTestMethod" wird ausgeführt und soll den pfad zu "MyDomain.sln" als debug meldung ausgeben

schreibe die methode "UnitTestMethod"
```

---

# Titel
gib der Aufgabe einen sprechenden Titel, damit Du sie im AI-Verlauf wieder findest.

##	Rolle
beschreibe, welche Rolle der AI-bot einnehmen soll:
- Software-Entwickler
- Software-Architekt
- Tester
- user, Anwender

```
Beispiel:
sei ein c#-Entwickler
```

## Aufgabe 1: Einzeiler für die Aufgabenbeschreibung
beschreibe den Auftrag an den AI-bot. 
- Teile die Aufgabe in Unteraufgaben. Jede Teilaufgabe soll mit einem Satz beschrieben werden können. Wenn nicht, teile weiter  
- Verwende für Teilaufgaben Spiegelstriche
- verweise auf konkrete code-Strukturen aus dem Anhang
- verweise auf zu verwendene patterns, Verfahren

```
Beispiel:
## task 2: restore revision instance
- there exists a number of revisions of ``MyDto``.
- the revision number 0 is the start instance.
- for each revision there exists a ``Dictionary<string,object> NewKeyValues`` which contains the changed properties and their new Values.
- the number of changed properties for each revision is normally lower than the number of properties of ``MyDto``.
- for each revision there may be another set of properties changed.

## task 2: initialize ``MyDto`` with a given set of KeyValues
the class ``MyDto`` has a number of public properties. Use a ``Dictionary<string,object> NewKeyValues`` to initialize ``MyDto``. the key of ``NewKeyValues`` is the name of the property of  ``MyDto`` the value is the value of the property. note that ``NewKeyValues`` not must contain all possible properties of ``MyDto``.


```

## Anhang
verwende den Anhang für code-Beispiele

```csharp
Dictionary<string,object> 

public class MyDto
{
	public string Name{get;set;}
	public int Age{get;set;}
	public string Street{get;set;}
	...
	
}
```
---
