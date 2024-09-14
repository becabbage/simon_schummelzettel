# Schummelzettel für Simon

Hier ist der erste Raspbery Pi Schummelzettel für Simon von Bernie.

## Befehle im "Terminal" 
Das Terminal ist das Fenster mit dem schwarzen Hintergrund. Hier findest du ein paar nützliche Befehle die wir schon mal verwendet haben.

| Befehl | Was macht der Befehl? | 
| -- | -- | 
| pwd | ...zeigt dir, in welchem Verzeichnis du gerade bist. | 
| ls -al | ...listet dir alle Dateien und Verzeichnisse auf. So siehst du, was in dem aktuellen Verzeichnis alles drin ist. *Tipp:* wenn du das **-al** weglässt, dann zeigt er nur die Dateinamen an. |
| cd xyz | ...wechselt in das Verzeichnis "xyz". Das geht natürlich nur, wenn das Verzeichnis xyz auch tatsächlich vorhanden ist. |
| conda env list | ...zeigt dir, welche Python Programmierumgebungen bei dir eingerichtet sind. |
| conda activate jumpandrun | ... aktiviert unsere Spiele Python Programmierumgebung. |
| python abc.py | ...führt das Python Programm "abc.py" aus. Das muss es natürlich geben. |

## Spiel starten

Der schnellste Weg um das Spiel zu starten ist:

* Terminal starten
* Folgende Befehle nach der Reihe eingeben:

```
conda activate jumpandrun
cd /home/simon/Daten/jumpandrun/kra_learning_code
python platformer.py
```

## Schummelzettel herunterladden

Beim ersten Mal ladest du den Schummelzettel folgendermaßen herunter:

```bash
cabbage@MSI-ubuntu:~/Daten$ git clone https://github.com/becabbage/simon_schummelzettel
Cloning into 'simon_schummelzettel'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.
cabbage@MSI-ubuntu:~/Daten$
```
## Schummelzettel aktualisieren

So kannst du nachsehen, ob ich auf dem Schummler etwas hinzugefügt oder ausgebessert oder ergänzt habe.

```
?
```
