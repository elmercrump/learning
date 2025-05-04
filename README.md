- `git init`: initialize current folder as a git repository
- `git clone <url>`: bring the git repo from <url> to current folder
- `git status`: Tells us what we need to know about our repository
- `git add <file>`: adds <file> to the staging area 
- `git commit`: open a text editor to write commit message
    - `git commit -m "MESSAGE"`: writes MESSAGE as a commit without a text editor

- `git log`: shows the log (history) of out commits
    - `git log --oneline`: shows the shorter oneline commit

- `git diff`: compare current uncommited state with last known git state
    - `git diff --staged`: runs git diff between the staging area and the last known state
- `git diff HEAD~<NUMBER>`: compares HEAD with the commit <NUMBER> ago (relative)
- `git diff <HASH>`: compares HEAD with the commit in <HASH>

-  `git log --oneline`: looking at the commit number
-  `git restore --source d766345 README.md`: d766345 was the initial commit number all changes are revereted to initial commit
-  `git add README.md`: Added the inital README.md to staging 
-  `git commit -m "Restored to original README.md"`: commiting to staging
-  `git push -u origin main`: piushing to main
-  `git log --online`: Shows the new commit number added 
-  `git restore --source 033d816 README.md`: switching from the initial commit back to the latest version
-  `git status`: Shows the status of the repository
-  `git restore --staged README.md`: staging the latest README.md 
-  `git add README.md`:  
-  `git commit -m "Restored to latest README.md"`:
-  `git push -u origin main`:

