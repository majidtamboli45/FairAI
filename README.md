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


____________________________________________________________________________________________________________________________________________________________________




Github Practical 2 :-  

git config --global user.name "majidtamboli45"

git config --global user.email "majidtamboli45@gmail.com"


mkdir Practical2

cd Practical2


git init


nano sample.txt


git add sample.txt

git commit -m "Initial commit"


git branch -M main


git remote add origin https://github.com/majidtamboli45/Practical2.git

git push -u origin main


# Create Feature Branch 1
git checkout -b feature1


nano sample.txt


git add sample.txt

git commit -m "Feature1 update"


git push -u origin feature1


git checkout main


# Create Feature Branch 2
git checkout -b feature2


nano sample.txt


git add sample.txt

git commit -m "Feature2 update"


git push -u origin feature2


git checkout main


# Merge feature1 into main
git merge feature1


git push origin main


# Merge feature2 into main (CONFLICT OCCURS HERE)
git merge feature2


# Resolve Conflict Here
nano sample.txt


git add sample.txt

git commit -m "Resolved merge conflict"


git push origin main


git branch

git status

git log --oneline












______________________________________________________________________________________________

jenkins password Reset :- sudo cat /var/lib/jenkins/secrets/initialAdminPassword


______________________________________________________________________________________

5 requirement.txt :- flask,numpy

docker build -t my-ai-app .

docker run -p 5000:5000 my-ai-app 

curl -X POST http://localhost:5000/predict \
-H "Content-Type: application/json" \
-d "{\"number\": 5}"


