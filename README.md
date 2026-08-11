# Min opgave
#Billede
![Mit billede](images/FCK.png)

#Link
[Besøg GitHub](htttps://github.com)

| Command                                             | Hvad betyder den?                                                      |
| --------------------------------------------------- | ---------------------------------------------------------------------- |
| `git status`                                        | Viser hvilken branch du er på, og om du har ændrede/committede filer.  |
| `git checkout nygren`                               | Skifter til branchen `nygren`.                                         |
| `git checkout main`                                 | Skifter til branchen `main`.                                           |
| `git switch nygren`                                 | Nyere alternativ til `git checkout nygren`. Skifter til `nygren`.      |
| `git pull`                                          | Henter ændringer fra GitHub og lægger dem ind i din lokale branch.     |
| `git push`                                          | Sender dine lokale commits op til GitHub.                              |
| `git push -u origin nygren`                         | Pusher `nygren` til GitHub og sætter den til at følge `origin/nygren`. |
| `git merge main`                                    | Fletter ændringer fra `main` ind i den branch, du står på.             |
| `git merge nygren`                                  | Fletter ændringer fra `nygren` ind i den branch, du står på.           |
| `git add .`                                         | Markerer alle ændrede filer som klar til commit.                       |
| `git commit -m "..."`                               | Gemmer dine ændringer som et commit med en beskrivelse.                |
| `git branch --set-upstream-to=origin/nygren nygren` | Fortæller Git, at din lokale `nygren` skal følge `nygren` på GitHub.   |
| `git checkout main -- filnavn`                      | Henter en bestemt fil fra `main` ind i den branch, du står på.         |
