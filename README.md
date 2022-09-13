# Lern-Bericht
## Einleitung
Wir haben im Lernatelier den Auftrag bekommen ein Zufallsspiel zu programmiern.

## Was habe ich gelernt?

Ich weiss nun wie ich Try und Catch verwenden kann und wie es programmiert wird.

## Beschreibung

Mit Try und Catch kann man das Projekt davor schützen, dass es bei einer Fehleingabe abstürzt. Try wird vor dem Code gesetzt und Catch nach dem Code, den man beschützen will. Man sollte aber Try und Catch nur über den Teil des Codes legen, wo ein Fehler passieren kann, den Try und Catch verlangsamen das Programm. Try überprüft jetzt bei jedem durch Gang, ob das Programm durchgeführt werden kann und wenn nicht wird der Codefluss zu Catch umgeleitet. Dort werden dann die Befehle ausgeben, die man bei einer Fehleingabe haben will.


```CSHARP
int i;
try
{
    // Wenn dieser Vorgang fehlschlägt, wird der Codefluss zu catch umgeleitet.
    Console.WriteLine("Geben sie eine Zahl ein: ");
    i = Convert.ToInt32(Console.ReadLine());
}
catch
{
    // Wenn der Codefluss zu catch kommt, werden diese Befehle ausgeführt.
    Console.WriteLine("Hat nicht funktioniert, war wohl keine Zahl.");
    Console.WriteLine("Starten sie das Programm neu.");
}
```

![Gif](https://github.com/TigerL06/Lern-Bericht/blob/main/Animation.gif?raw=true)

## Verifikation
Text: Im Text wird erklärt wie Try und Catch verwendet wird.
Code: Hier wird ein Codebeispiel gezeigt
Gift: Hier wird gezeigt, wie der Code funktioniert

# Reflektion zum Arbeitsprozess

👍 Das lief gut:
    Ich konnte konzentriert arbeiten.
    
    Ich habe die Aufträge gut erfühlt.
    
    Ich habe alle Aufträge zeitlich rechtzeitig fertig gestellt.

👎 Das lief schlecht:
   
   Wen Probleme aufgetaucht habe ich mich immer zwei Minuten lang aufgeregt.
    

**VBV**: 

Ich müsste mich bei nächsten Mal zusammenreisen und eine Lösung suchen.

