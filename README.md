# GIT

#### what is git?
- Free and open source version control sysytem.

#### What is version control ?
- The management od changes to documents, computer program, large web sites , and other collections of information.


## Git commands

- clone (cloning repository)
- add (Track new files and changes in git)
- commit (Record changes to the repository)
- push (Send all the changes to the remote repository)
- pull (Get the changes from the remote repository)
- status (Show the status of the repository)
- branch (Create and manage branches)
- checkout (Switch to a different branch)
- merge (Merge two branches)
- rebase (Move commits from one branch to another)
- diff (Compare two versions of a file)
- log (Show the history of a file)
- remote (Manage remote repositories)
- stash (Stash changes)
- reset (Reset the repository)
- fetch (Get updates from remote repository)
- tag (Create and manage tags)


```
git add .
git commit -m "title message" -m "description message"
git push origin master

```

- Connecting local machine to remote repository

```
ssh-keygen -t rsa -b 4096 -C "email@example.com"
ls | grep testkey

```

- Git repo locally

```
git init
git commit -m "title message" -m "description message"
git remote add origin repository_url
git push -u origin master

```

### Git Branching

- Branching is a way to divide your code into different versions.

```
git branch
git checkout -b new_branch_name
git checkout master
git checkout new_branch_name

```

-To delete a branch

```
git branch -d new_branch_name

```

```
git commit -am "add new file"

```

- To undo commits

```
git reset 

```
