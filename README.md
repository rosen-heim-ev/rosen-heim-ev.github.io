# rosen-heim-ev.github.io

## Arbeiten mit Git

Wenn ich einfach etwas eingebe, ist es da.

1. Wechsle auf `main branch` mit `git switch main`
2. Rufe den aktuellen Stand des remote (GitHub) ab mit `git fetch --prune`
3. Pull den aktuellen Stand mit `git pull`
4. Erstelle einen neuen Branch mit `git switch -c [branch-name]`
5. Ändere was Du willst.
6. Prüfe die Änderungen mit `git status` und `git diff` (mit Q wieder aus dem diff)
7. Bereite die gewünschten Dateien zum Speichern vor mit `git add path/to/file` 
8. Speichere die Änderungen in einem Commit mit `git commit -m "Commit-Message"`
9. Pushe den neuen Commit nach Github mit `git push`. Dieser Befehl wird beim ersten Mal fehlschlagen. Git wird dir den Befehl sagen, mit dem du pushen kannst. Copy/Past und ausführen.
10. Erstelle einen Pull-Request auf GitHub im Browser.
11. Merge den Pull-Request auf GitHub