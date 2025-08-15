…or create a new repository on the command line
echo "# APP_Peliculas_y_Series" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Monserl/APP_PyS.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Monserl/APP_PyS.git
git branch -M main
git push -u origin main

git branch -m main master
git fetch origin
git branch -u origin master
git remote set-head origin -a