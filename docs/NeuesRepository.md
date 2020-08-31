# Neues Repository erstellen

Um in einem lokalen **Arbeitsverzeichnis** auf deinem Computer ein **Git-Repository** zu initialisieren, kannst du im Terminal diesen Befehl eingeben:

```
git init
```

Alle Änderungen innerhalb dieser Verzeichnisstruktur werden nun verfolgt. Alle Dateien werden versioniert abgespeichert. Wenn du nun das Repository mit anderen teilen möchtest und es zentral "in der Cloud" haben möchtest, kannst du bei z.B. GitHub ein Repository erstellen und das lokale Repository mit dem bei GitHub verknüpfen.

-   Bei github.com anmelden (früher eröffnetes Konto vorausgesetzt)
-   Zu https://github.com/new wechseln
-   Felder «Name» (keine Leerzeichen, Striche verwenden) und «Description» ausfüllen
-   Bei «Private» oder «Public» wählen (Privat heisst, nur für dich sichtbar)
-   Mit «Create Repository» bestätigen

Danach kann das lokale Repository mit dem GitHub Repository wie folgt verknüpft werden:

```
git remote add origin git@github.com:nelkasovic/gitintro.git
```

Bitte beachte, dass bei git remote add origin der Name des eigenen Repository stehen muss.


### [Weiter](ReadmeErstellen.md)
