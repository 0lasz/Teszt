#Hello
…or create a new repository on the command line
echo "# Teszt" >> README.md #fájl létrehozása az első sorba ":# teszt" kerül
git init
git add README.md #staging changes, azaz a változások mentése
git commit -m "first commit"#változtatások jóváhagyása
git branch -M main #a fejlesztési ág átnevezése main-ra
git remote add origin https://github.com/0lasz/Teszt.git #távoli repo hozzáadása origin néven
git push -u origin main #a fejlesztési ág feltöltése élső alkalommal
…or push an existing repository from the command line
git remote add origin https://github.com/0lasz/Teszt.git
git branch -M main
git push -u origin main

Továbbui terminál parancsok:
giit pull origin main # a friss repoleetöltése
git remote -v #aktuális távoli repo lekérdezése
git status #change, stage, commit állapotának lekérdezése
git comfig --global --list #globális beállitások létrehozása
cd <directory naem>#ChangeDicectory
cd .. #egy mappával feljebb lép
  mkdir <dicectory name> #make dicectory
  rmdir <dicectory name> #remove dicectory
