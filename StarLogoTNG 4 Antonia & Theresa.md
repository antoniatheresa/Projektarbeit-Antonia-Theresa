#StarLogoTNG Part 4
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
