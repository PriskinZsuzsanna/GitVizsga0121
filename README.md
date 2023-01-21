Repository klónozása github-ról:
- git clone https://github.com/szabopeter92/git-vizsga0104.git

Git (re)inicializálása:
- git init

Main ág mentése az új létrehozása előtt:
- git add . -> összes untracked fájl hozzáadása a staging area-hoz
- git commit -m “main branch klónozva” -> verzió lokális mentése

Új ág létrehozása:
- git branch console

Váltás az új ágra:
- git checkout console

A README.md és a .gitignore fájl létrehozása után mentés:
- git add . 
- git commit -m "console ág létrehozva, readme.md, gitignore fájl létrehozva"

Gitignore fájl szerkesztése után
- git add .
- git commit -m "gitignore fájl szerkesztve"

App.js módosítása után:
- git add .
- git commit -m "app.js console ág elkészítve"

Style.css módosítása után:
- git add .
- git commit -m "style.css console ág elkészítve"

Readme fájl szerkesztése után
- git add .
- git commit -m "readme fájl szerkesztve"

Repo létrehozása a GitHub-on
Console ág mentése távoli repo-ba
- git push https://github.com/PriskinZsuzsanna/GitVizsga0121.git console



--------
plusz parancsok:

clear: terminálablak törlése
git status: git status lekérése
