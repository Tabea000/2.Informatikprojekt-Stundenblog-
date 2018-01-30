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
- Muffin als Ziel-> You won / Game over Mitte
- timer rückwärts
- Anpassen der Geschwindigkeit (verschiedene)
-Kleinigkeiten: Maus immer an gleichen Ort ebi Spielstart
- Beendigt: sichtbarer Erfolg
-> schnellere Erfolge bei ähnlichen Aufgaben

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


## <a name="acht"></a>Achte Informatikstunde am 17.1.2018

Heute wollten wir verschiedene Zwischenziele erreichen und schafften dies auch erfolgreich, auch wenn wir nur eine Einzelstunde Zeit hatten. Zunächst erntwickelten wir die Steuerung der Maus, die sich mit allen vier Pfeiltasten fortbewegen lässt. Daraufhin drehten wir die Katzen so, dass sie sich jetzt senkrecht über die stage bewegen. Mittels des Bausteins "if on edge, bounce" in forever"-"move x steps" konnten wir den einwandfreien Ablauf ermöglichen. Jetzt mussten wir uns der etwas schwierigeren Aufgabe zuwenden, dem Spiel ein Ende zu geben. Hierfür importierten wir für einen neuen sprite das costume "Game over!" nach Snap! und richteten ähnlich wie bei den vorhergegangenen Spielen einen timer ein, der sich jedoch noch jetzt jede Sekunde um den Wert Eins erhöht. 

Dem wollen wir uns jedoch erst nächte Stunde zuwenden, da zunächst für uns noch interessanter war, "Game over!" auch immer bei einer Berührung mit einem der Jäger erscheinen zu lassen. Auch nach einigen Versuchen konnten wir nicht herausfinden, wie man den "Game over!"-sprite mit dem Block koppeln könnte, der im script der Maus hinterlegt ist ("If sprite-Maus -> touching sprite-Jäger 1/2/3"), mussten wir kreativ werden. Wir ergänzten den sprite der Maus mit dem costume "Game over!" und fügten an den beschriebenen Block noch "set costume to >Game over!<" hinzu. Zwär hätte man nun den überflüssigen "Game over!"-sprite-block mit dem Block des Maus-sprites zusammenführen können, doch fanden wir den Effekt schöner, dass bei der Berührung der Maus mit einer Katze die Maus verschwindet, während bei Ablauf der Zeit die Maus auf der stage weiterhin sichtbar ist. 

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="sieben"></a>Siebte Informatikstunde am 15.12.2017
Pong + Cross the Road ->2 Stunden
-
-
-
-
Da wir nun endlich das Spiel Pong abgeschlossen haben, möchten wir uns nun einem dritten Projekt für unsere gleichwertige Leistung für das Fach Informatik entscheiden. Nach einigen Überlegungen hatte Tabea den Einfall "Cross the Road" nachzuprogrammieren. Es handelt sich auch hierbei wieder um ein berühmtes Spiel, bei welchem man ein Objekt über eine Straße lenkt, ohne fahrende/sich fortbewegende Gegenstände zu berühren und zu einem Ziel zu gelangen.

Wie in den vergangenen Projekten guckten wir auch diese Mal wieder auf Youtube nach einem Orientierungsbeispiel, auf das wir in Notfällen zurückgreifen können und entscheiden uns für <a href="https://www.youtube.com/watch?v=ntufT0tm6xM">diese Version</a>" der Ausführung. Im Anschluss eröffneten wir auf unserm gemeinsamen Snap!-Account ein neues Projekt naen "Crossy Road" und gestalteten die Basis des Projektes. Wir zeichneten mithilfe der Funktion "paint" eine Stage und gliederten sie in die Bereiche in denen sich der Spieler in sicherheit befindet und in die, wo die "Jäger-sprites" sich aufhalten, die Straße, die wir noch in senkrechte Bahnen für die Jäger einteilten. Zuletzt wählten wir die costumes der sprites aus. Für das Objekt, welches gesteuert wird, wurde es eine Maus und die Jäger wurden drei Katzen. So endete diese zweite Hälfte der Doppelstunde erstaunlich schnell und wir freuen uns bereits auf die kommenden Stunden.

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="sechs"></a>Sechste Informatikstunde am 8.12.2017
Pong ->2 Stunden

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="fünf"></a>Fünfte Informatikstunde am 6.12.2017
Das heutige Ziel für unsere Stunde war es, das Projekt "Shooting Game" abzuschließen. Dafür fehlte uns eigentlich nur die Eingliederung von "Won" in verschiedene Funktionen. Zunächst setzten wir fest, dass wenn mehr als sechs Punkte, durch das Abschießen der sechs Oktopusse erzielt wurden, Der sprite erscheint und alle anderen Abläufe des Spiels, bis zu einem erneuten Start durch Doppeklklick der Fahne, ausgesetzt werden. Zudem galt es zu beachten, dass zunächst zu dem richtigen costume gewechselt wird, bevor er Block bei dem Baustein "show" angelangt. Diesen Erfolg speicherten wir als "S.G. aktuell".

Da wir wir noch genug Zeit hatten, wollten wir, anstatt nur die "Won-Funktion" zuübertragen, auch versuchen, auf uns noch unbekannte Weise die kleineren Schwierigkeiten der Abläufe auszubessern. Überraschender Weise war es jedoch so, dass bei den ersten Abläufen auch mit dem Won-costume das Spiel fehlerfrei funktionierte. Und wir nur noch ein paar wenige Blöcke zusammenfügten, welche wir ursprünglich getrennt entwickelt hatten und deren Zusammenfügung für uns nun Sinn ergab. Somit entstand unsere offizielle Endversinon des "<a href="https://snap.berkeley.edu/snapsource/snap.html#present:Username=Juliane000&ProjectName=Shooting%20Game%20Versuch%20Won">Shooting Games</a>" die wir im "<a href="https://github.com/Tabea000/2.Informatikprojekt-Projektpraesentation-">Projektpräsentationsblog</a>" genauer erläutern.

Unser Fazit bei diesem Spiel ist überwiegend positiv, da wir fast ganz allein es schafften, ein Spiel zu programmieren, indem wir uns neue, aber auch schon bekannte Funktionen des Programmes Snap zu Nutzen machen konnten. Was uns leider etwas Einschränkte, waren die Grenzen, die dieses Programm hat. Zur Berechnung und Ausführung der von uns programmierten Einstellungen, benötigte Snap! beispielsweise bei dem Trefferbaustein aus unererfindlichen Gründen wesentlich länger und behinderte somit den Ablauf. Außerdem konnten wir auch bis zum Schluss den Fehler nicht beheben, dass bei mehrfachem Klicken auf ein Objekt auch die Punktanzahl weiter steigt und es somit theoretisch möglich wäre, nur durch einen Oktopuss fast seine 6 Punkte für ein erfolgreiches Spiel zu erreichen. Möglicherweise würde eine an die Farbe gekoppelte score hierbei weiterhelfen. Da dies jedoch eine Umstrukturierung nahezu aller scripts erfordern würde, möchten wir uns in den nächsten Stunden lieber wieder dem Spiel Pong zuwenden, bei welchem wir noch deutlich größere Lücken aufzuarbeiten haben.

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="vier"></a>Vierte Informatikstunde am 1.12.2017

Heute hatten wir erneut eine Doppelstunde Zeit, um uns weiter mit dem Shooting Game zu beschäftigen. Wir ergänzten unser Spiel durch die Funktion "timer", welcher rückwärts ablaufend, das Spiel zeitlich eingrenzt. Ist dieser gleich 0, taucht nun ein neu hinzugefügter Spite ("Game over!") auf, der das Spiel beendet. Außerdem fügten wir nochdie Variable der Punkte ein. Wird ein Treffer erzielt, also wird die "space-Taste" gedrückt, wenn mit der Linse auf ein Objekt fokussiert ist, verschwindet dieses und die Punktzahl erhöht sich um den Betrag 1. Da wir diesen Vorgang, welcher auch im Beispielvideo ungefähr gleich gestaltet wurde, etwas abrupt empfanden, entschieden wir uns, dass sich bei einem Treffer, nachdem die Punktzahl angestiegen ist, zunächst die Farbe des costumes ändert und daraufhin erst der sprite von der stage verschwindet.Dies machten wir durch die Nutzung des Bausteins, "set coloureffekt to x" möglich. Natürlich mussten wir im Gegenzug auch wieder für einen Neustart diesen Effekt auf 0 setzten. 

Da jetzt jedoch Schwierigkeiten im Ablauf auftrate, d.h. es verschwanden nicht mehr alle Oktopusse, die ihnre Farbe änderten, schlug uns Herr Buhl vor, den langen Block, der diesen Vorgang möglich machte als einen Baustein zu vereinen, da das Programm offensichtlich Schwierig hatte, den komplizierten Block einwandfrei umsetzten zu können. Hierfür wählten wir einen uns bekannten weg und erstellten so mithilfe der Funktion "make a block" den Baustein "Treffer", der eigentlich den reibungsfreien Ablauf garantieren sollte, da er zahlreiche Funktionen in einem vereint.

Trotz alledem war es so, dass noch immer nicht alle Oktopuss nach dem Farbumschwung nicht mehr sichtbar waren. Deshalb entfernten wir die Trefferfunktion wieder aus dem script und speicherten diesen Versuch aber als neue Datei namens "S.G. no change" ab. In den letzten Minuten der Stunde ergänzten wir den Sprite des "Game overs" mit dem costume "Won". Für die nächste Stunde nahmen wir uns vor, den Block für "Won" sowohl für die Spielversion mit, aber auch für die ohne Farbwechsel einzurichten und am Ende der Stunde mit diesem Minispiel abzuschließen.

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
