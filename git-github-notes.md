# Git & GitHub

## Version Control and DVCS

**Version Control** is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. 

A **Distributed Version Control systems (DVCS)** addresses the major vulnerability of the CVS: the server as a single point of failure. A DVCS allows clients to create mirrored repositories. Git is a DVCS. Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

The local Git repository has three components:
- Working Directory: The actual files reside here
- Index: The area used for staging
- Head: Points to the most recent commit
![Three Components](https://www.udemy.com/blog/wp-content/uploads/2015/08/image036.png)

## States
Files in Git can reside in three main states: committed, modified and staged.
- Committed: Data is securely stored in a local database
- Modified: File has been changed but not committed to the database
- Staged: Flagged a file’s changed version to be committed in the next snapshot

All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.
*Tracked files* can be modified, unmodified, or staged; they were part of the most recent file snapshot.
*Untracked files* were not in the last snapshot and do not currently reside in the staging area.

1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
1. You stage the modified file.
1. Then, you commit staged changes
![States of Git files](https://www.udemy.com/blog/wp-content/uploads/2015/08/image006.png)

### Check File Status
To determine the state of files, utilize the `git status` command.

