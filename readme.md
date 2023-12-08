# Git Ablauf

Szenario: wir starten in einem neuen Team und müssen den code clonen.

1. Suche einen Lokalen Ort/Ordner wo wir arbeiten können und starte das Terminal.

2. `git clone <url_zum_repo>`

3. Jetzt können wir loslegen und den Code bearbeiten.

4. Wenn wir ein Ergebnis haben, welches wir speichern, bzw. hochladen wollen.
Dann Lokal speicern und dann:

`git add .`
Schiebt die veränderten Dateien in den staging Berich

4. Optional können wir uns dies anzeigen lassen mit:

`git status`

5. Wir wollen nun die Veränderungen offizell ins Repository hinzufügen.

`git commit -m "modify readme and ad python file"`

6. Wir laden das Repository auf Github

`git push`


# Branches

Zeigt die existierenden Branches und verdeutlicht mit einem * den Zweig auf dem wir sind:

`git branch`

Erzeugt einen  neuen Branch:

`git branch <branch_name>`


Wechsle auf einen anderen Branch

`git checkout <branch_name>`

Es kann passieren das ein "merge confilct" entsteht, wenn die Zweige die zusammengeführt werden sollen.
Darauf müssen wir achten und git wird uns bitten den confict zu lösen.