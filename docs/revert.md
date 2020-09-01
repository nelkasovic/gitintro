# Änderungen rückgängig machen

Lokale Änderungen auf den **letzten Stand im HEAD** zurücksetzen kannst du mit:

```
git checkout -- <filename>
```

Änderungen, die du bereits zum Index hinzugefügt hast, bleiben bestehen. Wenn du deine **lokalen Änderungen komplett entfernen** möchtest, kannst du den letzten Stand vom entfernten Repository holen mit:

```
git fetch origin
git reset --hard origin/master
```

## Zu erledigen
- Änderungen wiederherstellen mit `git checkout`

### [Startseite](index.md) // [Zurück](merge.md) // [Weiter](branches.md)
