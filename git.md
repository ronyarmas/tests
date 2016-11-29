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

Use git <command> --help for more information on how to use some of the commands we discussed


These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects
