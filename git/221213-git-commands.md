The Commands and How to Use Git, I learned Today
1. Shell Commands
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
2. Vim Commands
 - i : enter the Insert mode only from Normal mode
 - V : enter the Visual mode only from Normal mode
 - esc : back to Normal mode
 - : : enter the Command mode
   - q : quit Vim mode
   - q! : quit Vim mode with discard any changes.
   - w : write
   - wq : write and quit
3. Before Start Git
 - Verify that the Program is intalled (git -v)
 - git Configuration
   1. git config --global user.name "user name"
   2. git config --global user.email "user email"
   3. git config --global core.editor "vim" (when you use vim)
   4. git config --global core.pager "anything you want" (this is command when you use print file)
   5. check config, before use git (git config --list)
 - Create repository and Clone
   1. do a Clone where you want make repository
4. How to Use Git
 - Commit prefix
   1. feat : about feature
   2. fix : when you fix error or bugs
   3. docs; document operation
   4. test : about test
   5. conf : about configuration 
   6. build : about bulid
 - Commit cautions
   1. Commit frequently as the smallest operational unit.
   2. All file changes made to the unit, must be included
   3. write log that everyone can understand.
   4. the title should be written simply, and the content should be written in senetence form and further explained
   5. Separate the title and content with a line
 - Process Flow
   1. working directory -> git add : staging area 
   2. staging area -> git commit : local repository
   3. local repository -> git push : remote repository
   4. remote repository -> git pull : local repository
   5. local repository -> git checkout : working directory
 - Type of License 
   1. MIT License
   2. Apache License 2.0
   3. GNU General Public License v3.0
