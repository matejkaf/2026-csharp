Basis Repository für C# Entwicklung in VSCode

HTL Coding Server: `coding.htl-braunau.at`

# Neues Projekt anlegen

Im Terminal:

```sh
./new.sh Uebung_1_1
```

Verwende die Übungsbezeichnung als Projektnamen.

# Starten des Compilers und Programm

Verwende Tastenkürzel `Ctrl-Shift-B` (Menü: Terminal > Run Build Task...)

Die angezeigten Fehler bleiben im PROBLEMS Tab bis zum nächsten ausführen von `Ctrl-Shift-B`.

Hintergrund: Beim starten über den Pfeil rechts oben im Editor Fenster (von der C# Extension zur Verfügung gestellt) werden einige Fehler nicht im PROBLEMS Tab dargestellt.

# VS Code Extensions

```sh
code --install-extension ms-dotnettools.csdevkit
```

# git Einstellungen


```sh
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
