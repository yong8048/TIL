# The Commands and How to Use Git, I learned Today

##. Shell Commands

 - . : current location
 - .. : parent location
 - pwd : printing working directory
 - ls : list up files at current location
 - cd : change directory
 - mkdir : Create directory
 - touch : Create file
 - mv : move directory(mv "directory name") or rename file(mv "current name" "new name")
 - cp : copy (cp "file or directory name" "directory name")
 - rm : remove (if remove directory, the directory must be empty. but if you want discard, use -r or -rf commands in front of directory name)
 - cat : print the contents of the file
 - vi : enter the Vim mode

##. Vim Commands

 - i : enter the Insert mode only from Normal mode
 - V : enter the Visual mode only from Normal mode
 - esc : back to Normal mode
 - : : enter the Command mode

### Command mode

 - q : quit Vim mode
 - q! : quit Vim mode with discard any changes.
 - w : write
 - wq : write and quit

##. Before Start Git

### Verify that the Program is intalled (git -v)

### git Configuration

- git config --global user.name "user name"
- git config --global user.email "user email"
- git config --global core.editor "vim" (when you use vim)
- git config --global core.pager "anything you want" (this is command when you use print file)
- check config, before use git (git config --list)

### Create repository and Clone

- do a Clone where you want make repository

##. How to Use Git

### Commit prefix

- feat : about feature
- fix : when you fix error or bugs
- docs; document operation
- test : about test
- conf : about configuration 
- build : about bulid

### Commit cautions

- Commit frequently as the smallest operational unit.
- All file changes made to the unit, must be included
- write log that everyone can understand.
- the title should be written simply, and the content should be written in senetence form and further explained
- Separate the title and content with a line

### Process Flow

- working directory -> git add : staging area 
- staging area -> git commit : local repository
- local repository -> git push : remote repository
- remote repository -> git pull : local repository
- local repository -> git checkout : working directory

## Type of License 

- MIT License
- Apache License 2.0
- GNU General Public License v3.0
