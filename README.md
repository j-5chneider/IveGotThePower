# What is this?

Wir erarbeiten und dokumentieren kollaborativ Skripte für Poweranalysen für jeweils unterschiedliche statistische Verfahren.

## To Do

1. Ihr richtet dieses R-Projekt auch **auf eurem Rechner** ein. Dazu benötigt ihr:
   - Installation von Git auf eurem Rechner (geht auch ohne Admin-Rechte). [Download hier (üblicherweise "standalone installer" und 64-bit Version)](https://www.git-scm.com/downloads).
   - Einen [Github-Account](https://github.com/).
   - Eine etablierte Verbindung zwischen eurem RStudio und Github. Siehe Erläuterungen unter "Personal Access Token" in [diesem Dokument](https://raw.githack.com/j-5chneider/howR/main/04_git-github-RStudio%20at%20DIPF/R-git-github.html#_Personal_Access_Token_(PAT)).
   - Ein neues R-Projekt, das auf dem GitHub Repo "IveGotThePower" basiert. Anleitung siehe unter "Connect Github and an R-project" in [diesem Dokument](https://raw.githack.com/j-5chneider/howR/main/04_git-github-RStudio%20at%20DIPF/R-git-github.html#_Connect_github_and_an_R-project). Wobei das Github-Projekt schon existiert! Und zwar ist es [dieses Repo hier](https://github.com/j-5chneider/IveGotThePower).
2. Ihr schreibt mir über RocketChat euren **GitHub-Namen**, dann vergebe ich euch Schreibrechte auf diesem Repo. Ansonsten habt ihr nur Leserechte.
3. Ihr schaut euch bis nächste Woche Donnerstag unser [noch leeres manual](https://raw.githack.com/j-5chneider/IveGotThePower/main/manual.html) an und überlegt euch für **welches statistische Verfahren** ihr Skripte für recherchieren wollt.
   - Schreibt in der Quarto-Markdown-Datei euren Namen hinter die entsprechende Überschrift (Datei "manual.qmd") in RStudio öffnen. Datei speichern und dann gerne noch rendern (Button "render").
4. Bis zu unserem **nächsten oder übernächsten Treffen** (nächste Sitzung erst 16.7.) pflegt ihr in das Quarto Dokument (manual.qmd) sowohl den R Code als auch Erklärungen/Interpretationen als Fließtext ein. Memes und alles was das Leben schöner macht, gerne willkommen (Bilder in Ordner "www" ablegen).
5. Besprechung der Ergebnisse dann jeweils in den Präsenztreffen

## Genereller Workflow

Wenn wir gemeinsam an einem R-Projekt über GitHub arbeiten, braucht es einen fixen Workflow.  
  
Jedes Mal, wenn ihr etwas im Projekt ändern möchtet, macht es Sinn

1. Direkt nach dem ihr das R-Projekt gestartet habt erst einmal zu **pullen** (siehe "git" Tab beim "Environment" Tab). Dann zieht RStudio den neuesten Stand des Projekts von GitHub, falls eine Person aus der Gruppe in der Zwischenzeit etwas verändert hat.
2. Dann eure Änderungen vornehmen.
3. Dann (oder gerne auch zwischendrin immer wieder) im git Tab auf **commit** clicken. Das erstellt eine neue Version der Datei, (ist äquivalent zu Dateiversionen z.B. in google docs). Dabei bitte eine **commit message** vergeben, was ihr im Vergleich zur letzten Version verändert habt. Das legt eine Versionshistorie der Datei an, die zunächst nur lokal auf eurem Rechner existiert. Das wird von Git gemacht, GitHub (das online Repo) weiß noch nichts davon.
4. Am Ende des Arbeitsprozesses (mindestens am Ende des Arbeitstags!) im git Tab auf **push** klicken. Erst jetzt sieht man die Versionen online auf GitHub und erst jetzt sind diese durch andere abrufbar (durch "pull").

Generell: Man kann durch Git und GitHub also später immer feststellen was zwischen den Versionen verändert wurde und von wem. Im Notfall kann man die Datei ohne Weiteres auf eine bestimmte Version zurücksetzen. Es geht also nichts verloren, selbst wenn wir mal etwas kaputt machen!