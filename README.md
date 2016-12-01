# Projektarbeit-Antonia-Theresa

##Gliederung

[StarLogoTNG](#Einführung)  
[1. Lernaktivität 1](#1)  
[2. Lernaktivität 2](#2)  
[3. Lernaktivität 3](#3)  
[4. Lernaktivität 4](#4)  
[5. Lernaktivität 5](#5)     
[6. Lernaktivität 6](#6)      
[7. Lernaktivität 7](#7)     
[8. Lernaktivität 8](#8)     
[9. Lernaktivität 9](#9)       
[10. Lernaktivität 10](#10)       
 
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

https://github.com/antoniatheresa/Projektarbeit-Antonia-Theresa/blob/master/StarLogoTNG%201%20Antonia%26Theresa.sltng

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

https://github.com/antoniatheresa/Projektarbeit-Antonia-Theresa/blob/master/StarLogoTNG%202%20Antonia%26Theresa.sltng

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

https://github.com/antoniatheresa/Projektarbeit-Antonia-Theresa/blob/master/StarLogoTNG%203%20Antonia%26Theresa.sltng           

Damit man eine Veränderung der "Agentenfarbe" im "Spaceland" erkennen kann, haben wir zunächst über die "Edit Breeds"-Funktion die 
Darstellung des "Agenten" im "Spaceland" in einen farblosen Eisbären verwandelt.
Für den ersten Schritt haben wir den "Create Turtles"- Block durch einen "Create do"- Block ersetzt, um die "Agenten" in drei 
verschiedene Farben zu unterteilen.
Nachdem wir dies getan hatten, konnten wir den "set color"- Befehl benutzen und eine Farbe auswählen, wir entschieden uns für "purple".
Im "Spaceland" waren nun alle "Agenten" in der Farbe "purple". Da wir aber verschiedenfarbige "Agenten" erstellen wollten, mussten wir nun 
einen "if-test-then"-Block einsetzen. Unser Plan war es, dass jeweils ein Drittel der Agenten "purple","blue" und "cyan" waren. 
Hierfür mussten wir in die "test"-Spalte einen "="-Block einsetzen.
In das erste Feld dieses Blockes fügten wir eine "3" hinzu, die wir mit dem Zusatz "random" versahen. In das zweite Feld setzten wir die
Variable "1" ein. Damit diese Agenten die Farbe "blue" annehmen, setzten wir in die "then"-Spalte einen "set color"-Block und fügten die
Cariable für die Farbe "blue" ein.
Die Farben sind jeweils einer Zahl von 1 bis 3 zugeordnet, damit jeweils ein Drittel der "Agenten" eine bestimmte Farbe trägt.
Für die Farbe "cyan" sind wir ähnlich vorgegangen. Wir haben wieder einen "if-test-then"-Block verwendet. In die "test"-Spalte setzten
wir wieder einen "="-Block ein und fügten in die erste Lücke die Variable "3" ein und ergänzten sie mit dem "random"-Block. In die 
zweite Lücke mussten wir nun aber die Variable "2" setzen, damit wir die Farbe "blue" nicht überschrieben. Damit nun ein Drittel der 
Agenten die Farbe "cyan" annimmt, setzten wir in die "then"-Spalte ein "set color" mit der Ergänzung "cyan" ein.

Nun sollen alle "Agenten" bei einer Kollision die Farbe tauschen. Um dieses zu errreichen, mussten wir den "Collision"-Block ergänzen. 
Wir wollten erreichen, dass ein "Agent", der einem anderen begegnet, seine Farbe annimmt, sofern diese verschieden sind.
Hierzu setzten wir erneut den "if-test-then"- Block ein und bezweckten so einen Farbwechsel bei einer Kollision.
Wir mussten hierfür jedoch in die "test"-Spalte einen "!="-Block setzen. In die erste Lücke fügten wir einen "color of ID"-Block ein, 
den wir mit dem Zusatz "collidee" ergänzten. Dieser Ausdruck bezeichnet nun die Farbe des "Agenten", mit dem der "Agent" zusammenstößt.
In die zweite Lücke setzten wir erneut einen "color of ID"-Block, ergänzten ihn jedoch mit einem "ID". Dieser Ausdruck bestimmt nun die 
Farbe des "Agenten". Mit der "then"-Spalte mussten wir den Farbwechsel beschreiben. Wir fügten also einen "set color"-Block ein und 
fügten "color of ID" und "collidee" hinzu, damit der "Agent" die Farbe des "Agenten" annimmt, mit dem er zusammenstößt. 
Den "if-test-then"-Block haben wir daraufhin kopiert und in die zweite Spalte des "collision"-Blocks gesetzt, damit auch der andere 
Kollisionspartner die Farbe wechselt.

Der nächste Schritt war, die "Agenten" gleicher Farbe bei einer Kollision sterben zu lassen.
Dazu haben wir in den "Collision"-Block einen "if-test-then"- Block hinzugefügt und die "test"-Spalte mit einem "="-Block versehen.
Dorthinein fügten wir in die erste Lücke einen "color of ID"-Block und den "collidee"-Ausdruck ein. In die zweite Lücke setzten wir 
auch einen "color of ID"-Block und ergänzten ihn mit dem Ausdruck "ID". Die Farbe des "Agenten" soll also nun bei einem Zusammenstoß
mit der Farbe des anderen "Agenten" übereinstimmen, damit der Befehl ausgeführt wird. 
Damit die Agenten sterben, wenn die "test"-Spalte zutrifft, fügten wir in die "then"-Spalte den Befehl "die" ein.
Auch bei diesem Schritt kopierten wir den "if-test-then"-Block und fügten ihn in der zweiten Spalte des "collision"-Blocks ein.

##Lernaktivität 4<a name="4"></a>

https://github.com/antoniatheresa/Projektarbeit-Antonia-Theresa/blob/master/SarLogoTNG%204%20Antonia%26Theresa.sltng

In dieser Lerneinheit haben wir nicht weiter an den "Turtles" gearbeitet, sondern ein neues Projekt hinzugefügt. Hierfür haben wir einen
"setup"-Block erstellt, den wir für die bessere Übersicht in "Rabbits, Objects" umbenannt haben. Zunächst mussten wir den 
"clear everyone"-Block einsetzen, um alle bisherigen "Agenten" aus dem "Spaceland" zu entfernen. Um nun neueund anders aussehende 
"Agenten" zu erstellen, gingen wir auf das Feld "Edit Breeds", wo wir einen "Agenten" in Form eines Hasens erstellten. Diesen 
nannten wir "Rabbit. Um ihn ins "spaceland" zu setzen fügten wir in den "Rabbit, Object"-Block einen "create rabbit"-Block und setzten die 
Anzahl auf 1. Damit der Hase irgendwo im "spaceland" auftaucht, setzten wir den "scatter everyone"-Befehl ein. 
Als nächstes wollten wir den Hasen mit den Pfeiltasten der Tatatur steuern. Wir erstellten also einen "forever"-Block, den wir wieder 
für die bessere Übersicht umbenannten, in diesem Fall "Tastatursteuerung". Wir setzten vier "if"-Blöcke in dei "Rabbit"-Spalte und 
setzten folgende Blöcke in die "test"-Spalten:
"keyboard up arrow"
"keyboard down arrow"
"keyboard left arrow"
"keyboard right arrow"
Wird die jeweilige Taste gedrückt wird die information "true" weitergegeben und der in der "then"-Spalte angegebene Befehl ausgeführt. 
Diese wären:
"keyboard up arrow" -- "forward" "2" -- der Agent bewegt sich nach Vorne
"keyboard down arrow" -- "back" "2" -- der Agent bewegt sich rückwärts
"keyboard left arrow" -- "left" "10" -- der Agent dreht sich um 10° nach Links
"keyboard right arrow" -- "right" "10" -- der Agent bewegt sich um 10° nach Rechts
Als nächstes sollten im "Spaceland" Objekte erstellt werden, die der Hase einsammelt. Dazu mussten zunächst die Objekte erstellt haben. Auch hierzu haben wir im "Edit Breeds"-Feld einen neuen "Agenten" in diesem Fall eine Karotte erstellt, den wir "Object" genannt haben. Im "setup"-Block haben wir den Befehl "create Object" eingesetzt. Allerdings zwischen den "scatter everyone und den
"Create Rabbit"-Block, damit auch die Karotten zufällig im "Spaceland" verteilt werden. Damit der Hase die Karotte bei einer 
Berührung einsammelt, haben wir einen "Collision"-Block erstellt. Wenn der Hase auf das "Object" trifft soll er etwas sagen. Dazu haben wir in dei "Rabbit"-Spalte einen "say"-Block gesetzt, und mit dem "abc"-Block einen Text erstellt. 
Durch denn "kill ID" "collide"-Block in der "Rabbit"-Spalte, verschwindet die Karotte bei einer Berührung mit dem Hasen. 
Als Bonus sollt ein Graf erstellt werden, der die Anzahl der eingesammelten Objekte (Punkte) des "Rabbit" angibt. Hierzu haben
Wir einen "line graph"-Block erstellt und die variable score in den "Runtime" bereich gesetzt. Für die Übersichtlichkeit 
Haben wir ihn in "Points Rabbit" umbenannt. Damit diese variable definiert wird haben wir sie im im "setup"-Block mithilfe des "set score"-Blocks und der Variable "0" auf 0 gesetzt. Im "collisionsblock" haben wir in der "Object"-Spalte einen "if-test-then"-Block gesetzt. In die "test"-Spalte haben wir die variable "true"-gesetzt und in die "then"-Spalte den Befehl "inc score" "1" eingefügt, damit im Falle eine Kollision der Punktestand um 1 erhöht wird. Diese Grafik kann man im "spaceland" ablesen.

##Lernaktivität 5<a name="5"></a>


##Lernaktivität 6<a name="6"></a>


##Lernaktivität 7<a name="7"></a>


##Lernaktivität 8<a name="8"></a>


##Lernaktivität 9<a name="9"></a>

https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Antonia%26Theresas%20Epidemie%20lol.sltng

###Homogene Epidemie<a name="1"></a> 

![Boolsche Varablen](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Boolsche.PNG)

Um eine homogene Epidemie zu erstellen, müssen wir zunächst eine boolsche Agentenvariable für den Zustand "ist krank" und "ist immun" einrichten.    
 
![Ansteckungsrate](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Ansteckungsrate.PNG)   

Als nächsten Schritt muss eine Ansteckungswahrscheinlichkeit festgelegt werden, nach der ein gewisser Prozentsatz der Population erkrankt sein soll.     
Dazu erstellen wir einen "slider"- Block, mit dem wir die "Ansteckungsrate" festlegen können.
Danach setzen wir an den "slider"-Block die globale Variable "shared number" und benennen sie in "Ansteckungsrate" um.     
Den maximalen Wert setzten wir dazu auf "100".      
Im Kontrollzentrum des "Spacerland" kann man nun über einen Schieberegler die Ansteckungsrate einstellen.    

![Populationsgröße](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Giraffen.PNG)      

Wie mit der Ansteckungsrate, fahren wir mit der Anzahl der Giraffen, also der Populationsgröße fort.     
Mithilfe eines "Slider"-Blocks und der Bedingung "Number Agents", setzen wir die maximale Populationsgröße auf 100 Giraffen/"Agenten".   
Dafür fügen wir an den "slider"-Block an die globale Variable "shared number" und benennen sie in "Number Agents" um.       
Wie die Ansteckungsrate kann die Populationsgröße im Kontrollzentrum des "Spaceland" eingestellt werden.    

![Homogene Epidemie](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Homogen.PNG)    

Nun können wir mit der Programmierung der homogen verteilten Epidemie beginnen.      
Hierzu erstellen wir zunächst einen "setup"-Block, den wir in "Homogen" umbenennen.      
Damit wir bei jedem Neustart mit einer neuen Population beginnen können, setzen wir zuerst den Befehl 
"clear everyone" ein.    
Somit wird bei jedem Neustart über den "Homogen"-"setup"-Block im Kontrollzentrum die alte Population gelöscht.  
Als nächstes setzen wir einen "create Agent-number-do"-Block ein.     
Über das "number"-Feld können wir die Größe der kreierten "Agenten" einstellen.    
Dazu setzen wir den "number Agents"-Block ein, bei dem wir die Anzahl über den Schieberegler im "Spaceland" einstellen können.      
In das "do"-Feld setzen wir zuerst den Befehl "set color"-"red" ein, damit alle gesunden "Agenten" die Farbe rot annehmen.      
Danach haben wir die Befehle "set ist krank"-"false" und "set ist immun"-"false" verwendet, um die boolschen Agentenvariabeln zu initialisieren.      
Denn diese sollen für die gesunden/roten "Agenten" als falsch eingestellt sein.    
Damit ein bestimmter Prozentsatz, homogen über die Population verteilt, krank werden kann, setzen wir einen "if-test-then"-Block ein.     
In die "test"-Spalte setzen wir die Bedingung "random"-"100" "ist kleiner oder gleich" "Ansteckungsrate".     
In die "then"-Spalte setzen wir den Befehl "set color"-"blue" und setzen die boolsche Agentenvariabel mit "set ist krank"-"true" auf "wahr".      
Wenn also die Bedingung in der "test"-Spalte zutrifft wird der Agent krank/blau.    
 
![Movement](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/movement.PNG)     

Damit sich die Krankheit ausbreiten kann, erstellen wir einen "forever"-Block und setzen einen Befehl für die Bewegung nach Vorne mit 1 bis 10 Schritten durch "forward"-"random"-"10" ein.     
Für die Drehung nach rechts in einem Winkel von 1-30 Grad setzen wir den Befehl "right"-"random"-"30" ein.      

###Infektionsherd<a name="2"></a> 
     
![Infektionsherd Epidemie](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Infektionsherd.PNG)        

Um einen Agenten die Epedemie auslösen zu lassen, brauchten wir einen Infektionsherd. 
Zuerst erstellten wir einen neuen Block, den wir "Infektionsherd" nannten und fügten die Variablen "clear everyone" hinzu, um mit einer neuen Population bei einem Neustart beginnen zu können. 

Danach setzten wir unter diese Variable den Block "create agent", um den Auslöser der Epidemie zu kreieren.
Zu diesem Block kamen die Variablen "number Agent", damit wir wie bei der homogenen Epidemie die Anzahl der Agenten im Spaceland einstellen konnten.
Dazu setzten wir mit "set color"-"red" die Farbe der gesunden Agenten auf rot.

Außerdem war ein "if then test"- Block nötig, da die Farbe sich bei einer Ensteckung ändern sollte. 

![Gleichung Infektonsherd](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Gleichung%20Infektionsherd.PNG) 

Nachdem wir dies getan hatten, erstellten wir eine lange Variable nach Vorlage des des Satzes des Pythagoras.
Sie bewirkt, dass sich nur die Agenten infizieren, die sich in einem bestimmten Bereich des "Spaceland" aufhalten.

![Ansteckungsrate](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Ansteckungsrate.PNG)  

Dies geschieht in Verbindung mit der Ansteckungsrate, welche wir ja im Spaceland variabel verwenden können. Wie diese Kollision zu programmieren ist, beschreiben wir im nächsten Schritt noch genauer. 


###Ansteckung<a name="3"></a> 
    
![Ansteckung durch Kollision](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Ansteckung.PNG)     

Um sich gegenseitig anstecken zu können, müssen sich ein kranker und ein gesunder "Agent" begegnen.     
Wir mussten also einen "Collisions"-Blog für eine Kollision zwischen zwei Agenten verwenden.     
Um eine Bedingung für die Ansteckung einstellen zu können, setzten wir einen "if-test-then"-Block in eine freies Feld des "Collision"-Blocks.     
Da sich nur "Agenten" unterschiedlicher Farbe, also unterschiedlicher Gesundheitszustände, anstecken sollen, setzten wir in das "test"-Feld die Bedingung "color of ID"-"collidee" "ungleich" "color of ID"-"ID".     
Als nächstes sollen sich die "Agenten" nur zu einer bestimmten Wahrscheinlichket anstecken. Also setzten wir einen weiteren "if-test-then"-Block in die "test"-Spalte des anderen "if-test-then"-Blocks.    
In die "test"-Spalte setzten wir die Bedingung "random"-"100" "ist kleiner oder gleich" "Ansteckungsrate".  
Somit erhalten wir eine Ansteckunswahrscheinlichkeit in Prozent.   
Trifft diese Bedingung zu, soll der "Agent" erkranken.   
Also setzten wir in die "then"-Spalte den Befehl "set color"-blue" und die boolsche Agentenvariable "ist krank" mit "set ist krank" auf "true".   

![Ansteckungsrate](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Ansteckungsrate.PNG)      

Die Ansteckungsrate ist mit einem "slider"-Block im Kontrollzentrum des "Spaceland" durch einen Schieberegler einstellbar.   
Dafür setzen wir an den "slider"-Block die globale Variable "shared number" und benennen sie in "Ansteckungsrate" um.   

###Immunität<a name="4"></a> 

![Homogene Epidemie](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Homogen.PNG)        
![Boolsche Variablen](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Boolsche.PNG)    

Damit wir eine Immunität einrichten zu können müssen wir eine boolsche Agentenvariable für den Zustand "ist immun" erstellen. 

![Movement](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/movement.PNG)     
   
Die kranken Agenten sollen nach einiger Zeit zu einer bestimmten Wahrscheinlickeit wieder gesund werden.   
Daraufhin sollen sie immun sein.   
Dazu setzen wir in den "forever"-Block einen "if-test-then"-Block ein.    
In die "test"-Spalte setzen wir die Bedingung "random"-"100" "ist kleiner oder gleich" "Heilingschance".    
Trifft dieser ZUstand bei einem "Agenten" ein, soll er die Befehle aus der "then"-Spalte ausführen.   
Diese wären:  
"Set color"-"green" und "set ist immun"-"true".  
Er soll also die Farbe grün für immun annehmen, weshalb wir die boolsche Agentenvariable für "ist immun" auf "true" eingestellt haben.

![Heilungschance](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Heilungschance.PNG) 

Die Heilungschance soll wieder mit einem Schieberegler im Spacland einstellbar sein.   
Hierzu erstellen wir einen "slider"-Block für die Heilunschance ein und setzen wieder den maximalen Wert auf "100".   
Dafür setzen wir an den "slider"-Block die globale Variable "shared number" und benennen sie in "Heilungschance" um.   

###Gesundheitszustand<a name="5"></a> 

![Gesundheitszustand](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Gesundheitszustand.PNG)  

Die "Agenten" in der Epidemie-Simulation nehmen nun nach und nach unterschiedliche Farben an (rot, blau, grün).
Damit wir die Verteilung der unterschiedlichen Gesundheitszustände (Gesund, Krank, Immun) im Blick haben können,
erstellten wir ein Säulendiagramm, in dem wir die unterschiedlichen Mengen der Gesundheitszustände mittels Säulen
in den entsprechenden Farben ablesen können.    
Hierzu mussten wir zunächst einen "bar graph"-Block erstellen, den wir zuerst in "Gesundheitszustand" umbenannten.   
In den offenen "socks" konnten wir nun die Bedingungen für die einzelnen Säulen eingeben.  
Wir erstellten zuerst die Säule, die die Menge der gesunden "Agenten" angibt.   
Hierzu setzten wir an der "Gesundheitszustand"-Block den Befehl "count Agent with" an. 
Die Bedingung sollte in diesem Fall sein:    
"red" "=" "color of ID"-"ID". Die Farbe des Agenten sollte also der Farbe rot entsprechen, um in dieser Säule gezählt zu werden.    
Ähnlich fuhren wir bei den weiteren freien Feldern des "Gesundheitszustand"-Blocks fort.    
Wir setzten wieder den Befehl "count Agent with" ein.    
In dieser Säule sollte aber die Anzahl der kranken "Agenten" dargestellt werden.   
Hierzu setzten wir als Bedingung "blue" "=" "color of ID"-"ID" ein.    
Für die immunen Agenten fuhren wir genau so fort, setzten jedoch als Bedingung "yellow" "=" "color of ID"-"ID" ein.     
Nun konnte man zu Beginn der Simulation und im laufe der Simulation die Anzahl der gesunden, kranken und immunen Agenten im "Kontrollzentrum" des "Spaceland" ablesen.    
Durch Anklicken der Grafik kann der Zahlenbereich der Y- bzw. X-Achse ablesen.    
 
![Grafik Gesundheitszustand](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Grafik.PNG)   

Startet man die Simulation einer homogenen Epidemie sieht das Bild mit den gesunden (rot), kranken (blau), und immunen (gelb) "Agenten" im "Spaceland" so aus: 
  
![Epidemie Grafik](https://github.com/antoniatheresa/Epidemie-Projekt/blob/master/Epidemie%20Grafik.PNG)    
##Lernaktivität 10<a name="10"></a>
