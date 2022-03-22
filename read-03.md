# [Git Tutorial - a Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensiv)

## Version Control Systems

**Version Control (VCS)** - a system that allows you to track the various versions of a file or files. Git is an example of a Version Control System (VCS). The ability to track changes allows one to see where potential mistakes were made along the way. These systems also make collaboration among teams possible.

**Local Version Control** - a database on your computer that stores changes to files

**Centralized Version Control (CVCS)** - A single server stores all changes and versions, which can be accessed by various users. This allows for easy collaboration, allowing programmers to see the changes made by others in certain files.

**Distributed Version Control** - allows clients to create mirrored repositories. DVCS are useful in the event of the failure of the CVCS server.

## What is Git?

Git is a DVCS that stores data in snapshots. Each time a changed version of a project is saved (commit), Git stores a snapshot of the file. 

- Git relies on local operations - allowing one to work on a project offline. 

- Git tracks changes and is set up to minimize the accidental loss of data. 

- Git resides in three states:
  - Committed - Data is stored in a local database
  - Modified - A file is changed but not committed to the database
  - Staged - a file’s changed version to be committed in the next snapshot

***Git is one of the most utilized Version Control Systems in the world.***

## Cloning

Cloning is how you can copy an existing Git repository from a server and move it to your local system. Cloning copies all versions of a file for a project. Once the clone is local you can make (or add) changes in your code editor and through the terminal you can commit and then push those changes to the server, in this case GitHub.

### Essential Commands 

**git status** - determines the state of a file

**git add *filename*** - adds your new file

**git commit -m “comments”** - saves your changes to your file and allows you to comment what changes were made. Comments are essential to letting others know what you have done. *As a rule keep all comments to 50 characters or less.*

**git commit -a** - commits a snapshot of all changes to tracked files

**git push origin main** - pushes changes from the local to the remote repository[^1].

[^1]: this whole page was made in VSCode and pushed to GitHub via the terminal!
