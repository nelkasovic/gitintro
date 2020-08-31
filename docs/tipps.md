# Tipps & Tricks

Git User-Konfiguration:

```
git config user.name "Nermin Elkasovic"
```

Git User-Konfiguration:

```
git config user.email "email@address.com"
```

Git User-Konfiguration auflisten:

```
git config --list
```

Eingebaute git-GUI:

```
gitk
```

Farbige Konsolenausgabe:

```
git config color.ui true
```

Eine Zeile pro Commit in der Logausgabe:

```
git config format.pretty oneline
```

Interaktives Hinzufügen von Änderungen:

```
git add -i
```

Letzten Commit herunterladen, ändern und überschreiben:

```
git reset --soft HEAD~1
git add .
git commit -m "Nachricht"
git push -f
```


### [Weiter](index.md)
