# gitgud-github

basic github stuff, e.g. tutorials, shortcuts, links, guides, etc.

## basic git commands
- `$ git init`
- $ git clone
- $ git status
- $ git add:
  - $ git add .
  - $ git add <filename.ending>
- $ git rm -r <filename.ending>
- $ git commit -m "commit msg"
- $ git push:
  - $ git push -u origin master
  - $ git push <branchname>
- $ git pull:
  - $ git pull origin master
  -
- $ git log
- $ git checkout master

## create new local repo
- create project folder
- $ git init (create basic git files)
- create example file:
  - $ type nul  > readme.md
  - or: $ echo "# gitgud-github" >> README.md

## connect local-repo to github-repo
- $ git remote add origin git@github.com:username/new_repo
- or: $ git remote add origin https://github.com/username/repo-name.git

## create branch (~beta, ~preview, ~test)
