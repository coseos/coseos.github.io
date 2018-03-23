
#bash



## Ein einfaches Shell-Script

Mit unserem ersten Shell-Script geben wir den Text "Hello World"
aus. Die Ausgabe erfolgt auf über die Standardausgabe ('stdout')
auf die Konsole.

In der ersten Zeile des Shell-Sriptes verwenden wir die 'Shebang'.
Die bash führt die Datei mit dem in dieser Zeile angebenen
Programm aus. Das Programm 'bash' befindet sich im Verzeichnis
/bin/. Damit kann ein Shell-Script immer mit der richtigen Shell
ausgeführt werden.

Steht als erstes Zeichen in einer Zeile ein Hashtag ('#'), dann
wird die Zeile als Kommentar angesehen und nicht ausgeführt.
Befindet sich in der ersten Zeile.

In der vierten Zeile befindet sich die Ausgabe. Dazu verwenden
wir den Shell-Befehl 'echo'. Den Text übergeben wir in
Anführungszeichen und damit als einzelnen String.

Ohne die Anführungszeichen erhält der Befehl 'echo' die einzelnen
Worte als Argument und gibt diese aus. Befinden sich zwischen
zwei Argumenten mehr als ein Leerzeichen, wird dafür nur ein
einzelnes Leerzeichen ausgeben.

Damit das Shell-Script ausgeführt werden kann, 

    chmod +x helloworld.sh

Ausgeführt wird das Shell-Script mit

    $ ./helloworld.sh

Der "Pfad" ('./') vor dem Shell-Script ist notwendig, da in Linux
ein Script grundsätzlich nicht aus dem aktuellen Verzeichnis
ausgeführt wird. Geben wir das aktuelle Verzeichnis ('.'), als Pfad
vor dem Script an, wird es auch ausgeführt.



