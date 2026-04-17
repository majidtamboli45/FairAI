GitHub Practical :- 1

git config --global user.name "majidtamboli45"

git config --global user.email "majidtamboli45@gmail.com"

mkdir P1
cd P1

git init

echo "# First Practical Implementation" > README.md
touch .gitignore

git add .
git commit -m "Initial commit"

git branch -M main

git remote add origin https://github.com/majidtamboli45/P1.git

git push -u origin main

touch script.py

nano script.py

git add .

git commit -m "Added Python script file"

git push

git remote -v


________________________________________________________________________________________________________________________________________________________________________________________________________
