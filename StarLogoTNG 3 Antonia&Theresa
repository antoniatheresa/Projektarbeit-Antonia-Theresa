#StarLogoTNG Part 3
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
