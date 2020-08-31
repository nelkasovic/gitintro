# Änderungen hochladen
Die Änderungen sind jetzt im HEAD deines lokalen Repositories. Um die Änderungen an dein entferntes Repository zu senden, führe aus:

```
git push -u origin master
```

Du kannst master auch mit einem beliebigen anderen Branch ersetzen, mehr über Branches erfährst du später. Danach kannst du den Parameter -u weglassen. Verwende zukünftig nur noch:

```
git push origin master
```

#### Sonderfall

Wenn du dein lokales Repository nicht von einem entfernten geklont hast und du diese aber mit einem anderen Repository verbinden möchtest, musst du dieses mit hinzufügen:

```
git remote add origin <server>
```

Danach bist du bereit, deine Änderungen hochzuladen.


### [Weiter](Pull.md)