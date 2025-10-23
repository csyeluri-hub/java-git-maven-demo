\# CE - Week 1 Assignment 1 - Git Commands Used



git config --global user.name "Your Name"

git config --global user.email "your@email.com"

git init

git add .

git commit -m "initial commit"

git branch -M main

git remote add origin https://github.com/csyeluri-hub/java-git-maven-demo.git

git push -u origin main

git checkout -b feature/hello-world

git add src/Hello.java

git commit -m "feat: add Hello.java"

git push -u origin feature/hello-world

git checkout main

git merge feature/hello-world

git branch -d feature/hello-world

git push origin --delete feature/hello-world



