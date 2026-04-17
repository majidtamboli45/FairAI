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

4] jenkins password Reset :- sudo cat /var/lib/jenkins/secrets/initialAdminPassword


______________________________________________________________________________________

5 requirement.txt :- flask,numpy

docker build -t my-ai-app .

docker run -p 5000:5000 my-ai-app 

curl -X POST http://localhost:5000/predict \
-H "Content-Type: application/json" \
-d "{\"number\": 5}"



_________________________________________________________________________________________________________________

6] 
# 1]backend:-
1]app.py
2]requirements.txt(flask,pymango)
3] Dockerfile:-

FROM python:3.9
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY app.py .
CMD ["python", "app.py"]

# 2] Frontend
1]index.html
<!DOCTYPE html>
<html>
<head>
<title>AI Docker App</title>
</head>
<body>
<h1>AI Docker Application</h1>
<p>Frontend running in Nginx container.</p>
</body>
</html>
2]Dockerfile
FROM nginx:alpine 
COPY index.html /usr/share/nginx/html/index.html

# 3] docker-compose.yml

run :- docker-compose up –build


_________________________________________________________________________________________________________________________________________________________

Jenkins :- 9

create project folder 
create app.py(in vscode)

in vscode terminal:
git init
git add .
git commit -m "first commit"

on github create repo

copy commands like

git branch -M main
git remote add origin
git push  -u origin

run that permission commnad

sudo chown 

on jenkins 

create new item
select free style project

ok

in triggers:-
select poll SCM
Add H/1 * * * *

in build steps select execute shell

in execute shell

cd "file path"(which is obtained from the vscode terminal by running the pwd)

save

build now

console output

change the code in local machine then also commit it to github so the changes get reflected on jenkins


__________________________________________________________________________________________________________________________________________________


minicube - 7

docker --version

minikube version

minikube start --driver=docker

kubectl get node


on kubernet in yml file paste give code

check the 2 pods and deployment proper

then again create another yml




