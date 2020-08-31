# Tagging

Es wird empfohlen, für Software Releasestags zu verwenden. Dies ist ein bekanntes Konzept, das es schon mit SVN gab. Du kannst einen neuen Tag namens 1.0.0 mit folgendem Befehl erstellen:

```
git tag 1.0.0 1b2e1d63ff
```

1b2e1d63ff steht für die ersten 10 Zeichen der Commit-Id, die du mit deinem Tag referenzieren möchtest. Du erhältst die Liste der Commit-IDs mit:

```
git log
```

Du kannst auch weniger Zeichen verwenden, es muss einfach eindeutig sein.

![Git-Workflow](./assets/images/git_releases.png)

### [Weiter](collaborators.md)
