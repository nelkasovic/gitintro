# Änderungen rückgängig machen

Falls du mal etwas falsch machst, kannst du die lokalen Änderungen auf den letzten Stand im HEAD zurücksetzen mit:

```
git checkout -- <filename>
```

Änderungen, die du bereits zum Index hinzugefügt hast, bleiben bestehen.

Wenn du aber deine lokalen Änderungen komplett entfernen möchtest, holst du dir den letzten Stand vom entfernten Repository mit folgenden Befehlen:

```
git fetch origin
git reset --hard origin/master
```

### [Weiter](branches.md)
