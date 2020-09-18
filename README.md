# fop-gitignore
.gitignore file voor het vak Advanced Programming (Intellij)

Voeg deze .gitignore file toe aan ieder project die je wil pushen naar een remote repository.
Dit zorgt ervoor dat bepaalde bestanden en mappen niet worden mee opgenomen door git.

## Verwijder bestanden in git
Heb je toch enkele bestanden toegevoegd aan je remote git repository en wens je deze weer te verwijderen, zodat deze niet langer getrackt worden door git?

Voor een afzonderlijke file: 
```
git rm --cached file1.txt
```

Voor een directory
```
git rm -r --cached directory
```
