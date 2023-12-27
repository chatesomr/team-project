Link to video (Part 1) - https://www.youtube.com/watch?v=hrTQipWp6co

Link to part - 2 of Git Tutorial - https://www.youtube.com/watch?v=1ibmWyt8hfw

Completed part-1

git-tutorial is here - D:\HTML Training\GitTutorial

Now working on Part-2
Time reached - 39.43 mins..

Below are the commands for pushing changes in the project.
git add .
git commit -m "Version 13" <!-- The message is Version 13  -->
git push origin master

git remote -v === This will show the link to the repository.

Use below command -
git log --all --graph <!-- This checks after pushing information to github -->

Use -
git fetch <!-- This shows the current state in github -->

Use -
git pull origin master <!-- T0 pull the master branch - from github  -->

How to add a project in GIT

1. git init
2. create a commit - type - git add ., then git commit -m "Message"
3. Create a GitHub repository - Use -
4. git remote add origin https://github.com/chatesomr/practice.git
5. Then use - git push origin master

How to clone an existing repository to computer - Use -
git clone https://github.com/chatesomr/newPractice-project.git newFolderName

- remember to choose the folder first
- this help us save some steps for setup.

---

echo "# newPractice-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/chatesomr/newPractice-project.git
git push -u origin main

git remote add origin https://github.com/chatesomr/newPractice-project.git
git branch -M main
git push -u origin main
