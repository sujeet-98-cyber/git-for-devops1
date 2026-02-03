1. Directory & File Setup

Commands to create and manage directories and files.

mkdir git-for-devops

cd git-for-devops

pwd

ls

ls -l

ls -a

touch file.txt

2. Initialize Git Repository

Used to start Git version control in a directory.

git init

3. Check Repository Status

Shows staged, unstaged, and untracked files.

git status

4. Add Files to Staging Area

Stages files before committing.

git add nibbi.txt

git add nibba.txt

git add .

5. Remove Files from Staging Area

Used when a file is added to staging by mistake.

git rm --cached nibba.txt

6. Commit Changes

Saves staged changes to the repository.

git commit -m "adding nibba nibbi"

git commit -m "added new changes to nibbi"

7. Configure Git User

Required for identifying commit author.

git config --global user.name "sujeet-98-DevOps"

git config --global user.email "sujeetsing9896@gmail.com"

8. View Commit History

Displays commit logs.

git log

git log --oneline

9. Branch Management

Create, list, and switch branches.

git branch

git checkout -b dev

git checkout dev

git checkout master

git checkout -b test

git checkout test

10. Edit Files

Used to modify file content.

vim nibbi.txt

vi hello-dosto.txt

11. Utility & Cleanup Commands

Helpful Linux commands during Git practice.

rm hello-dosto.txt

clear

history

✅ DevOps Best Practices

Run git status frequently

Use branches like dev and test

Write meaningful commit messages

Git is core to CI/CD, Kubernetes, Jenkins, and automation
