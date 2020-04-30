# Version Control
    A system that allows you  to revisit various versions of a file or set of files by recording changes.
    It can revert to a previous version, track modifications and modifying individuals and compare changes

## Types of version control

- Local  VCS - One database on your harddrive that shows changes to files

- Centralized CVS - a single server storing all changes and file versions, which can be accessed by various clients

- Distributed DVCS - allows clients to create mirrored repositories

# Git

Git is a DVCS that stores data in a file system made up of snapshots

Each time you save (commit) a changed version of your project Git creates a snapshot of the file and stores a reference to it. If the file hasn't changed Git stores a reference to the stored version

### What Git does

- relies on local operations
- tracks changes and detects file corruption or loss of info

### 3 states of Git files

1. Committed - data is securely stored in a local database
1. Modified - file is changed but not committed to the database
1. Staged - Flagged a files changed version to be committed in the next snapshot

Git includes GUI tools or 3rd party tools can be used for a particular platform

## Importing

* switch to target project directory
    'git help [command]'

* Use the git init command

    'git init'

*a new sub dir has been created named .git that is not tracked yet*

ACP  
* Add - git add [filename]
* Commit -git commit -m "message"
* Push - git push origin master

link to the document from reading assignment
(Git reading assignment)[https://blog.udemy.com/git-tutorial-a-comprehensive-guide/]

link to my learning journal
(learning journal)[https://github.com/deannaj401/learning-journal]




