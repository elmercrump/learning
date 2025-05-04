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

