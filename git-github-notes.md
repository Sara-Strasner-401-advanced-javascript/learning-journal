# Git & GitHub

## Version Control and DVCS

**Version Control** is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. 

A **Distributed Version Control systems (DVCS)** addresses the major vulnerability of the CVS: the server as a single point of failure. A DVCS allows clients to create mirrored repositories. Git is a DVCS. Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

The local Git repository has three components:
- Working Directory: The actual files reside here
- Index: The area used for staging
- Head: Points to the most recent commit

## States
Files in Git can reside in three main states: committed, modified and staged.
- Committed: Data is securely stored in a local database
- Modified: File has been changed but not committed to the database
- Staged: Flagged a file’s changed version to be committed in the next snapshot

### Check File Status
To determine the state of files, utilize the `git status` command:

