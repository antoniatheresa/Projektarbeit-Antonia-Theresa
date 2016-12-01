# Projektarbeit-Antonia-Theresa

##Gliederung

[StarLogoTNG](#Einführung)  
[1. Lernaktivität 1](#1)  
[2. Lernaktivität 2](#2)  
[3. Lernaktivität 3](#3)  
[4. Lernaktivität 4](#4)  
[5. Lernaktivität 5](#5) 

##StarLogoTNG<a name="Einführung"></a> 

StarLogoTNG ist ein Simulationsprogramm für die Blockprogrammiersprache.     
Es ist übersichtlich aufgebaut und besteht aus zwei Feldern, dem Programmierfeld und dem Spaceland, 
wo man die Aktionen und Fortschritte der Agenten verfolgen kann.     
     
Die Agenten können mehrere Formen annehmen und so individuell eingestellt werden.      
Auch die Umgebung kann durch Gebäude, Pflanzen und andere Gegenstände ergänzt werden.      
Durch das Zusammensetzen verschiedener Böcke, die in Ordnern am Rande des Programmierfeldes untergebracht sind, 
kann man die Agenten zu verschiedenen Handlungen bewegen.     
Diese Blöcke, welche man bei StarLogoTNG als "Variablen" bezeichnet, sind nach Verwendungszweck sortiert, 
zum Beispiel findet man Variablen für Gleichungssysteme im Ordner "math", der Ordner für Farben nennt sich "colors" etc.     

Dadurch hat man also diverse Möglichkeiten, dem Spiel eine bestimmte Richtung zu geben.

Man kann also wie in unserem folgenden Projekt Epedemien mit Infektionsherden, Ansteckungen,
Immunität und Gesundheitszuständen entstehen zu lassen, den Agenten bestimmte Aufgaben zu geben, 
wie etwa einen Baum in der Umgebung hochzuklettern, oder Unterhaltungen zwischen Agenten bei einer Kollision zu starten.   
 
Zur vielfältigeren Gestaltung kann man die "Agenten" mischen und verschiedene Tiere und Farben einsetzen,
sowie im Spaceland die Sicht des Agenten und des Betrachters ein- und verstellen.    
Ebenfalls im Spaceland kann man bei Betätigung des "forever"- Buttons die aktuellen Änderungen sichern und die "Agenten" 
beliebig agieren lassen sowie die vorher im Programmierfeld eingestellten Aktionen beobachten und Verbesserungen vornehmen.     
 
Fehler in der Programmierung machen sich also gleich bemerkbar, 
wenn sich im Spaceland keine Änderungen zeigen oder eine Variable nicht kompatibel für einen bestimmten Block ist. 
Durch dieses "Schlüssel-Schloss- Prinzip" ist das Programm für Anfänger geeignet und gut verständlich.   
Auch die gut sortierten Variablen und Ordner machen das Programmieren einfach.   

Durch die vielen Gestaltungsmöglichkeiten ist StarLogoTNG sehr vielfältig nutzbar, 
wird aber nicht unübersichtlich, da das Programmierfeld am rechten oberen Rand nochmal in kleinerer Ausfühtung angezeigt wird, 
um den Überblick zu wahren, wenn die Variablen und Blöcke zu komplex werden. 

##Lernaktivität 1<a name="1"></a>

Zuerst haben wir einen setup Block erstellt und durch den Befehl "clear everyone" alle "Agenten/turtles" aus dem "Spaceland" entfernt.
Dann haben wir mit dem Befehl "create turtles" einen "Agenten" erstellt und die "Agentennummer" auf 1 gesetzt. 
Wählt man nun im "Spaceland" den "setup" Block aus, erscheint genau ein "Agent" im "Spaceland". 
Um alle "Agenten" im "Spaceland" mit einem Befehl steuern zu können, haben wir einen "forever-Block" eingefügt. 
Mit den Befehlen zur Bewegung "forward" bewegt sich der "Agent" im "Spaceland" solange vorwärts, bis man den Befehl
stoppt.
Als nächstes haben wir die Schrittzahl auf "10 steps" gestellt und einen Befehl zur Rechtsdrehung um 90 Grad hinzugefügt (right degs). 
Dadurch bewegt sich der "Agent" im "Spaceland" nun im Quadrat.
Diese Bewegung kann man mit dem "forever"-Knopf im "Spaceland" starten und stoppen. Der Befehl gilt für alle "Agenten" im "Spaceland"
und wird von oben nach unten im "forever"-Block abgespielt, bis der Befehl gestoppt wird.
Als Nächstes haben wir die Perspektive geändert, indem wir auf den "Agenten" geklickt und so seine Position und Farbe eingestellt haben.
Anschließend haben wir im "Spaceland" den Befehl "Agent View" ausgeführt und so unsere Perspektive geändert.

##Lernaktivität 2<a name="2"></a>

Als Erstes haben wir einen "Slider"-Block verwendet, um die Zahl der "Agenten" mit einem Regler im "Spaceland" beliebig regulieren
zu können. Dazu haben wir an diesen "Slider"-Block eine globale Variable gesetzt ("shared number"),
die wir zur besseren Übrsicht in "Number Turtles" umbenannt haben. 
Diese Variable haben wir an den "create turtles"- Befehl angeschlossen, damit die gewünschte "Agenten"-Zahl über den "setup"-Block im 
"Spaceland" eingefügt wird.
Um die "Agenten" im "Spaceland" zu verteilen, haben wir an den "setup"-Block einen "scatter"-Befehl gesetzt.
Damit sich die Agenten willkürlich im "Spaceland" bewegen, haben wir vor jede Variable im "forever"-Block einen "random"-Block hinzugefügt.
Als nächstes haben wir einen "Collision"-Block eingesetzt,um die "Agenten" bei einem Zusammenstoß sprechen zu lassen. 
Hierfür haben wir in die freien Felder dieses Blockes die "say"-Funktion aktiviert. Um diesen Text zu bestimmen, haben wir die
"abc"-Variable verwendet und den Text zu "Hallo" bzw. "Oh Hallo" geändert.

##Lernaktivität 3<a name="3"></a>


##Lernaktivität 4<a name="4"></a>


##Lernaktivität 5<a name="5"></a>
