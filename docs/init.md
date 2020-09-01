# Neues Repository erstellen

Um in einem lokalen **Arbeitsverzeichnis** auf deinem Computer ein **Git-Repository** zu initialisieren, kannst du im Terminal diesen Befehl eingeben:

```
git init
```

Alle Änderungen in diesem Verzeichnis werden verfolgt und Dateien versioniert. Wenn du das Repository mit anderen teilen willst, kannst du bei z.B. GitHub ein Repository erstellen und das lokale Repository mit dem bei GitHub verknüpfen.

-   Bei github.com anmelden (früher eröffnetes Konto vorausgesetzt)
-   Zu https://github.com/new wechseln
-   Felder «Name» (keine Leerzeichen, Striche verwenden) und «Description» ausfüllen
-   Bei «Private» oder «Public» wählen (Privat heisst, nur für dich sichtbar)
-   Mit «Create Repository» bestätigen

Danach kann das lokale Repository mit dem GitHub Repository verknüpft werden mit:

```
git remote add origin git@github.com:nelkasovic/gitintro.git
```

Nach `git remote add origin` muss der Name des eigenen Repository stehen.


### [Startseite](start.md) // [Weiter](echo.md)
