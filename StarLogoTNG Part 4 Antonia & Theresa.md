#StarLogoTNG Part 1
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
Als nächstes sollten im "Spaceland" Objekte erstellt werden, die der Hase einsammelt. 
