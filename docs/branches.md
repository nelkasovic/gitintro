# Branches

Branches werden benutzt, um verschiedene Funktionen isoliert voneinander zu entwickeln. Der master-Branch ist der "Standard"-Branch, wenn du ein neues Repository erstellst. Du solltest aber für die Entwicklung andere Branches verwenden und diese dann in den Master-Branch zusammenführen (mergen).

![Git-Workflow](./assets/images/git_branching.png)

Neuen Branch mit dem Namen "feature-x" **erstellen** und auschecken kannst du mit:

```
git checkout -b feature-x
```

Zum master-Branch zurück **wechseln** kannst du mit:

```
git checkout master
```

Den eben erstellten Branch wieder **löschen** kannst du mit:

```
git branch -d feature_x
```

Den neuen Branch ins entfernte Repository hochladen kannst du mit:

```
git push origin <branch>
```

Ein neuer Branch ist für andere erst dann verfügbar, wenn du diesen hochgeladen hast.

### [Startseite](start.md) // [Weiter](tagging.md)
