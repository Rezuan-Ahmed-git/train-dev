1. Initial commit:

---

(Phase: New project)

1. git init
2. git add . / -A
3. git commit -m
4. git branch -M main
5. git remote add origin https://github.com/Rezuan-Ahmed-git/train-dev.git
6. git push -u origin main

### Commit:

1. git commit -m ""
2. git commit -m "Header" -m "Description" -m "Footer"
   git log --oneline
   git log --oneline --graph --decorate
3. git commit --amend

## Branch:

1. git branch
2. git branch -r (check remote branch)
3. git switch <branch_name>
4. git checkout <branch_name>
5. git checkout -b <new_branch_name> (create a new branch and also switch to the created branch)

## Delete Local and Remote Branch:

1. git branch -d feature/login-page (-d means delete safely. delete the local branch if it is merged. if it is not merged then it will show error:
   error: The branch 'feature/login-page' is not fully merged.
   )
   If you don't want to merge but delete then use the force delete version:
2. git branch -D feature/login-page

(Phase: Contribute)

1. Clone the project
   git clone https://github.com/Rezuan-Ahmed-git/train-dev.git
   cd train-dev

clone specific branch:
git clone -b <branch-name> <link>

2. Check branch & pull latest updates
   git branch # see current branch
   git fetch origin
   git pull origin dev # always update your dev branch

3. Create a new branch for your feature
   git checkout -b feature/login-page

4. Work & commit your changes
   git add .
   git commit -m "Add login page UI and validation"

5. Push your feature branch
   git push -u origin feature/login-page

6. Create Pull Request (PR)

### Trying something new
