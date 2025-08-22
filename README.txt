1. 'git init' - Powers your folder to be managed by git , and initialises a new empty repository and 
it also creates .git folder that has all the relevant logic to manage versions
of your project .

there are 3 areas in the git ecosystem

2. working areas -> There can be a bunch of files that arre not currently handled by git.
It means that changes done or to be done in those files are not managed by git yet. A file 
which is in working area is considered to be not in the staging area . when we do 'git status'
and we see a bunch if 'untracted files' then these are actually called to be in the working area .

3. staging areas -> it is going to tell 
What all files are going to be part of the next version that we will create . 
This staging area is the place where git knows what changes will be done from the last version to the next
version.

4. repository areas : This area actually contains the details of all your previous registered version.
and the files in this area, git already manages them and knows their version history.


5. 'git add <file>' -> this moves from working area to staging area.

6. 'git rm --cache <file>' -> moves file back from staging area to working area.

7. 'commit' -> commit is a particular version of the project . it captures a snapshot of the project's staged changes and creates a 
version out of it.

8. 'git commit' -> registers staging changes to a commit.

9. 'git log' -> list down all the commits of the repository . if u want to quit out of git log prompt press 'q'.