# Git

## Befehle:

https://git-scm.com/docs/git-commit

- `git remote -v` -> zeigt die Version, mit der der aktuelle git remote verbunden ist

## Andere Cheatsheets

- http://ndpsoftware.com/git-cheatsheet.html#loc=local_repo; (bunt)
- https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf (PDF)

## Neues Repository über GitHub anlegen

1. Repository auf GitHub erstellen
2. Repository clonen (einfachste Weg) -> Alternativen werden auf Übersichtseite angezeigt
3. Terminal `git clone (url)`
4. `npm init -y`(-y alle Fragen werden direkt mit Ja beantwortet) -> Package.json wird angelegt
5. `npm install --save-dev parcel-bundler sass` -> installiert Parcel und Sass als Developer Dependency (-D ist identisch)
6. Scripte erstellen: `"dev": "parcel src/*.html", "build": "parcel build src/*.html",` -> abhängig vom Pfad der index.html
7. .gitignore erstellen:

```
.cache
dist
node_modules
DS_Store
```

8. Git Commit
9. Git Push

## vorhandenes Projekt in ein Repository laden

1. `mkdir ORDNER`
2. `echo "ORDNER" >> README.md"` -> erstellt README.md mit dem Inhalt "ORDNER"
3. `git init`
4. `git add README.md`
5. `git commit -m "first commit"`
6. `git remote add origin git@PFAD`
7. `push -u origin master`-> Wo soll dieser Branch mit verbunden werden (origin=github.com)
8. Parcel usw. installieren

## Die wesentlichen Schritte

_Git - Versionskontrolle_

1. **init:** _Projekt initialisieren._ Es wird ein unsichtbarer Ordner angelegt (.git) in dem sich alle Informationen über Änderungen an Dateien befinden

2. **stage:** _Sammeln der Änderungen._ Änderungen an Dateien werden nicht automatisch übernommen. Vor dem synchroniesieren wird manuell eine Auswahl der zu synchronisierenden Dateien getroffen _(stage changes)_.
3. **commit** _Synchronisieren._ Um die gesammelten Dateien von der stage mit der git-Historie zu synchronisieren muss ein commit gemacht werden. Es ist üblich mit jedem commit eine kurze und präzise Nachricht zu hinterlassen in der beschrieben wird was durch den jeweiligen commit hinzugefügt wird

_GitHub - Hoster und Kollaboration (local & remote)_

4. **master & branch** _Kollaboration._ Der Stamm (master), welcher später aus dem fertigen Projekt besteht, kann auch Abzweigungen haben (branch). Der _master_ sollte fertiggestellte bzw. funktionierende code-Abschnitte beinhalten, also eine stabile Version. _Branches_ dienen dazu die Kollaboration zu erleichtern, aber auch die Arbeit an neuen oder experimentellen Ideen und Features sicher zu stellen.

5. **merge** _Zusammenlegen._ Wenn ein branch bereit ist Teil der stabilen Version zu werden wird ein merge initiiert um den code zusammen zu legen.

<img alt="GitHub explained" src="https://blog.red-badger.com/hubfs/Imported_Blog_Media/img-257.jpg" width="500px"><br>
_Quelle: blog.red-badger.com/2016/11/29/gitgithub-in-plain-english_

#### Kernbegriffe

- **Repository:** Das Verzeichnis in dem sich alle Dateien des Projektes befinden
- **Local:** auf einem Laptop oder Desktop Computer (offline)
- **Remote:** Online bzw. auf einem Server "in der cloud"
- **Pull Request:** a Github tool that allows users to easily see the changes (the difference or "diff") that a feature branch is proposing as well as discuss any tweaks that said branch might require before it is merged into master <br><br>
- **Stage:** Sammlung der Änderungen _vor_ dem commit
- **Commit:** Synchronisieren der Änderungen mit dem master/branch
- **Master:** Stabiler Stamm des Projektes
- **Branch:** Die Baustelle. Neue, unfertige, work in progress, experimentelle Features & Ideen
- **Collab:** Kollaboration zwischen mehreren Menschen (oder K.I.?)
- **Merge:** Zusammenlegen von branch und master. Änderungen und ergänzungen werden besprochen und kontrolliert vereint

## Gitignore

https://git-scm.com/docs/gitignore

## Benennung der Commits

immer ein Verb enthalten

```

```
