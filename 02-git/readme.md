# GIT
Distributed Version Control System

## After create a new repo
    echo "# huge-bootcamp-html-css" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/edgarflorez/huge-bootcamp-html-css.git
    git push -u origin master

## Steps for git Demo 
1. Create a repository
2. Commit a file change
3. Push changes
4. See it on GitHub
5. Clone the repository
6. Push different changes
7. How to fix a conflict merge

## Wiki

- `hash` or `sha` : unique id for a commit

## Commands
- `git init`    : initialize a repo
- `git status` : Allow us to see the actual status of our local repository
- `git add .`   : Add all the unstaged files to stage
- `git commit -m "My message"` : Commit some files with a message
- `git push origin master` : Push your staged changes from local to the remote repo
- `git pull origin master` : bring remote changes to local
- `git clone https://github.com/....` : Make a clone of the remote repo into the current folder, creates a connections by default.

## links
- [Git - the simple guide](https://rogerdudler.github.io/git-guide/)
- [A Grip On Git](https://agripongit.vincenttunru.com/)
- [Markdown](https://www.markdownguide.org/)