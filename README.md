Git-Befehle und Begriffe


Grundlegende Git-Begriffe
Begriffe definieren und erklären




Unterschiede von Lokale vs. Entfernte Repositories



Lokale Repository-Befehle



Arbeit mit Branches



Änderungsverwaltung



Historie und Logs



Entfernte Repository-Befehle
Repository klonen und synchronisieren




Änderungen zurücksetzen



GIT MERGEKONFLIKTE

-Ursachen - Ein Konflikt entsteht, wenn zwei Entwickler die gleichen Zeilen in einer Datei ändern. Oder wenn einer die Datei löscht und der andere sie verändert.

-Mergekonflikte erkennen - Git zeigt Konflikte mit besonderen Zeichen an: <<<<<<< HEAD, ======= und >>>>>>> branch-name.

-Merge-Konflikte lösen - 1. Git meldet Konflikt
                         2. Dateien mit Konflikt öffnen
                            Git markiert den Konflikt mit:
                            <<<<<<< HEAD
                            Dein Code
                            =======
                            Anderer Code
                            >>>>>>> branch-name
                         3. 1=Entweder eigenen Code behalten
                            2=Anderen Code übernehmen
                            3=Beides kombinieren
                            Dann Konfliktmarker (<<<<<<<, =======, >>>>>>>) entfernen
                         4. Datei mit git add *, git commit speichern
                            
-Vorbeugung - Oft mit dem Haupt-Branch abgleichen und nur kleine Änderungen in einzelnen Commits machen.




NÜTZLICHE NAVIGATIONSBEFEHLE

-ls – Zeigt alle Dateien und Ordner im aktuellen Verzeichnis an

-cd <ordner> – Wechselt in das angegebene Verzeichnis

-cd (ohne Parameter) – Wechselt ins Home Verzeichnis


Lokale Repositories
Repository erstellen und Status prüfen


