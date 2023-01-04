Git inicializálása
git init parancsal


Letöltjük a file-okat
A git pull https://github.com/szabopeter92/git-vizsga0104.git parancsal.

git status
Git státusz ellenőrzése

.gitignore file létrehozása
A touch .gitignore commandal

Megadjuk mely kiterjesztésű file-oakt ignorálja
*.txt
*.doc
*.docx
*.pdf


File-ok követésének megadása
A git add . parancsal.

Fő ág létrehozása 
a git commit -m

mellék ág létrehozása
git branch console

váltás az ágak között
git checkout console

módosítások végrehajtása a feladat szerint a js és a css file-ba majd commit
git add .
git commit -m

megadott módosítások után
git checkout main

README.md file hozzáadása és kitöltése majd commit
git add .
git commit -m 

File-ok feltöltése repository-ba
git remote add origin https://github.com/NekoYuu-bot/fabryzoltan-git-01.04..git
git push -u origin main
git push -u origin console



