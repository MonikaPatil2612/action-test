### Install 

**Github for Windows**
https://windows.github.com

**Github for Mac**
https://mac.github.com

**Github for All Patforms**
https://git-scm.com

Git distrubutions for Linux and POSIX systems are availabele on the official Git SCM website.

### Configure tooling
Configure user information for all local repositories

1. **$ git config --global user.name "[name]"**

    Set the name tytou want attached to your commit transactions

2. **$ git config --global user.email "[email address]"**

    Sets the email you want attached to your commit transactions

3. **$ git config --global color.ui auto**

    Enables helpful colorization of command line output

### Branches

Branches are an imporatant part of working with Git any commits you make will be made on the branch you ar currently "checked out" to. Use git status to see which branch that is.

1. **$ git branch [branch-name]**

    Creates a new branch.
   
2. **$ git checkout [branch-name]**

    Switches to the specified branch and updates the working directory.
   
3. **$ git merge [branch]**

    Combines the specified branch's history into the current branch. This is usually done in pull requests, but iis an important Git opration.

4. **$ git branch -d [branch-name]**

    Delete specified brach.   

### Create repositories

When working with new repository, you only need to do it once, either locally,then push to GitHub, or by cloning an existing repository.

1. **$ git init**

    turn an existing directory into a git repository.

2. **$git clone [url]**

   Clone (download) a repository that already exosts on GitHub, including all of the files, brances, and commits.

### Synchronize changes

Synchronize your local repository with the remote repository on GitHub.com

1. **$ git fetch**

   Downloads all history from the remote tracking branches

2. **$ git merge**

   Combines remotes tracking branch into current local branch

3. **$ git push**

   Uploads all local branch commite to GitHub

4. **$ git pull**

    Updates your current local working branch with all new commits from the corresponding remoate branche on GitHub.**git pull** is a combination of **git fetch** and **git merge**

### Make changes
Browse and inspect the evolution of project files

1. **$ git log**

   Lists version history for the current branch

2. **$ git log --follow [file]**

   Lists version history for a file,including renames
   
3. **$ git diff [first-branch]..[second-branch]**

   Shows content differences between two branches

4. **$ git show [commit]**

   Outputs metadata and content changes of the specified commit

5. **$ git add [file]**

    Snapshots the file in preparatyion for versioning

6. **$ git commit -m "[descriptive message]"**

     Records file snapshots permanently in version history

### Redo commits

Erase mistakes and craft replacement history

1. **$ git reset [commit]**

    Undoes all commit after [commit], preserving changes locally

2. **$ git reset --hard [commit]**

    Discords all history and changes back to the specified commit
