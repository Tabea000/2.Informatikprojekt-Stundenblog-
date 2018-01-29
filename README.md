# <a name="Inhaltsverzeichnis"></a> Stundenblog von Tabea und Juliane

## Informatikprojekt 2


[Erste Stunde](#eins)

[Zweite Stunde](#zwei)

[Dritte Stunde](#drei)

[Vierte Stunde](#vier)

[Fünfte Stunde](#fünf)

[Sechste Stunde](#sechs)

[Siebte Stunde](#sieben)

[Achte Stunde](#acht)

[Neunte Stunde](#neun)

[Zehnte Stunde](#zehn)

[Elfte Stunde](#elf)



![bsp applab](https://raw.githubusercontent.com/Tabea000/2.Informatikprojekt-Stundenblog-/master/Bildverzeichnis/CtR%201_Pr%C3%A4stentation.png?raw=true "Screenshot von AppLab")

### <a name="elf"></a>Elfte Informatikstunde am 26.1.2018
-1 Stunde
- Vorarbeiten zu hause: zuschneiden auf Word- kein Ergebnis, Speichern auf PC wieder ganzer screenshot
- Besprechungen
- Hochladen der Screenshots von CtR und SG
- Zuscheiden auf paint

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="zehnt"></a>Zehnte Informatikstunde am 24.1.2018
-1 Stunde
- Umstrukturierung Stundenblog -> oben nach unten
- Erstellen des Bioldverzeichnisses
- Besprechen des weiteren Vorgehens 
- kleinere Korrekturen an Spielen (Zusammenfürgen von kleinen Einzelblöcken; z.B. Hide+timer0 -> Ablauf timer)

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="neun"></a>Neunte Informatikstunde am 19.1.2018
Cross the Road -> 2 Stunden
- 3Katzen-> 1 Katze + 4 andere= höhere Schwierigkeit
- Muffin als Ziel-> You won
- timer rückwärts
- Anpassen der Geschwindigkeit (verschiedene)
- Beendigt: sichtbarer Erfolg
-> schnellere Erfolge bei ähnlichen Aufgaben

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


## <a name="acht"></a>Achte Informatikstunde am 17.1.2018
Cross the Road -> 1 Stunde
- Schreiben der Scripts für die sprites Katzen und Maus
- timer-> Game over
- touching Katzen -> Game over 

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="sieben"></a>Siebte Informatikstunde am 15.12.2017
Pong + Cross the Road ->2 Stunden
-
-
-
-
-2. Stunde: Überlegungen-welches neue Spiel? CtR Idee
- Suche auf youtube->  https://www.youtube.com/watch?v=ntufT0tm6xM
- neues Projekt auf snap
- Festlegen Hintergrund (Malen)
- Auswählen der sprites: Katzen und Maus

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="sechs"></a>Sechste Informatikstunde am 8.12.2017
Pong ->2 Stunden

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="fünf"></a>Fünfte Informatikstunde am 6.12.2017
Shooting Game 1 stunde 
SG aktuell-> won ohne change 
Schwierigkeiten durch alternatives Skript -> SG Versuch Won aus Grundversion mit Farbenwechsel = Endersion
-> Farben, Timer, Points
Won

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="vier"></a>Vierte Informatikstunde am 1.12.2017
Shooting Game 2Stunden
- Timer und Punkte
- Treffer-> Farbwechsel
- Game over
- Schwierigkeiten treten beim Ablauf 
- kein vollständiges verschwinden nach Schuss
- Versuch SG no change -> points lösen kein Won aus

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)

### <a name="drei"></a>Dritte Informatikstunde am 24.11.2017 ->2stunden

Nachdem unsere Fortschritte bei "Pong" etwas nachließen und wir in der letzten Stunde nicht so recht wussten, wie wir nun fortfahren sollten um die aufgekommenen Schwierigkeiten bezüglich der score zu beseitigen, beschlossen wir, heute uns zunächst einem anderen Projekt zuzuwenden und dieses in den folgenden Stunden abzuschließen, um nicht die Freude an dieser Art zu programmieren zu verlieren. 
Da unser Ziel für diese Projektarbeit es war, mehrere kleine populäre Minispiele nachzuprogrammieren, überlegten wir uns einige Zeit lang, womit wir uns nun beschäftigen könnten. Unsere Wahl fiel auf ein "Shooting Game", das jedem bekannt sein sollte. Von einem solchen Spiel fanden wir eine ausführliche Anleitung für Snap auf Youtube, auf welche das wir uns bei Schwierigkeiten beziehen könnten, jedoch wollten wir zunächst den Anfang allein angehen.

Dies ist der Link zu dem "<a href="https://www.youtube.com/watch?v=Un5c_LeC0Pw">Shooting Game auf Youtube</a>" von dem wir uns wahrscheinlich in den folgenden Stunden Anregungen holen werden.

Daraufhin begannen wir mit den grundlegenden Elementen des Spieles. Zunächst erstellten wir die Linse zum fokussieren auf das Ziel. Wir gestalteten diesen Sprite durch die Funktion "Paint a costume" und die Möglichkeiten dabei exakte Kreise und Geraden zu zeichen. Das script ermöglicht es, die Linse durch Mausbewegungen zu lenken. Genauere Erläuterungen der Blöcke und deren Funktionsweisen erfolgen wie bereits zuvor erläutert wieder im "<a href="https://github.com/Tabea000/2.Informatikprojekt-Projektpraesentation-">Projektpräsentationsblog</a>" . Ebenfalls wählten den background der stage aus den Vorlagen aus und importierten die costumes der abzuschießenden Objekte aus. In diesem Fall wurden es bei uns Oktopusse, welche zwischen zwei costumes alle 0,2 s wechseln. Wir vervielfachten diese auf eine Anzah von 6, nachdem wir das script für die random-Bewegung geschrieben hatte.  
Zuletzt holten wir uns eine Anregung, da wir nicht ganz wussten, wie wir es einrichten konnten, dass die Linse auch ein Abschießen des Objektes einleiten könnte. Dabei erkannten wir, dass wir über den "mouse-pointer" eine Verbindung zum betroffenen sprite und der "space-Taste" gezogen werden. Zusammengefügt in einem Block war es uns am Ende der Stunde wirkich möglich, dass der sich wegende Oktopus durch die Linse, welche sich mit dem "mouse-pointer" bewegt, abgeschossen werden konnte und im Anschluss, durch "hide" von der stage verschwand.


[→Inhaltsverzeichnis](#Inhaltsverzeichnis)

### <a name="zwei"></a>Zweite Informatikstunde am 22.11.2017
Pong
-1 Stunde

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="eins"></a>Erste Informatikstunde am 10.11.2017
Überlegungen + Pong
- 2Stunden
https://www.youtube.com/watch?v=9TYA3XTpYGM



[→Inhaltsverzeichnis](#Inhaltsverzeichnis)
