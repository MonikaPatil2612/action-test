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
