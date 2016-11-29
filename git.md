Common Git commands

Command Description
init    creates a new git repository
add copies files (at their current state) to the stage
status  check which files have changes or staged for commit
commit  saves a snapshot of the stage as a commit
reset   go back to a specific snapshot
checkout    switch between commits or branches
diff    view list of changes between two commits
merge   combines two branches together
log displays a list of your commits
push    uploads your changes to a remote repository
pull    downloads changes from a remote repository
clone   copies a remote repository locally

Create a new directory called git_test, open it and perform a

git init
Add & Commit

You can propose changes using

git add <filename>
or add all files to staging

git add .
Check the files you added before saving changes

git status
To save a snapshot of the changes locally

git commit -m "Commit message"
Undo

If we want to view the commit history

git log

Go back to a previous snapshot of your changes

git reset
