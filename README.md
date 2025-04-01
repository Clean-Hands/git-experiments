# git-experiments

## Part 1
### Lazuli
1. Cloned the repo with `git clone https://github.com/Clean-Hands/git-experiments.git`
2. Created a file with `vi oven.txt`
3. Added it with `git add oven.txt`
4. Committed it with `git commit -m "Valid question"`
5. Pushed with `git push`

### Ruben
1. Cloned the repo with `git clone https://github.com/Clean-Hands/git-experiments.git`
2. Pulled all changes with `git pull`
3. Looked at the file with `cat oven.txt`

## Part 2
### Lazuli
1. Looked at the commit history with `git log`
2. Created a branch called "wahoo" with `git branch wahoo`
3. Switched to the new branch with `git switch wahoo`
4. Created a new file for the new branch with `vi yippee`
5. Added the file using `git add yippee`
5. Committed the file using `git commit -m "lugee"`
6. Tried to push with `git push` but got an error
7. Fixed the error by running the suggested command `git push --set-upstream origin wahoo`
8. Went to GitHub and created a pull request

### Ruben
1. Went to GitHub and accepted the pull request
2. Ran `git log`

## Part 3
### Ruben
1. Edited a file with `vi yippee`
2. Pushed changes with `git add yippee`, `git commit -m "Causing issues"`, and then `git push`.

### Lazuli
1. Switched back to the main branch with `git switch main`
2. Made conflicting changes with `vi yippee`
3. Committed changes using `git commit -m "i hope this works"`
4. Pulled remote changes with `git pull`, which notified me that I had a conflict
5. Ran `git pull --rebase` to handle the merge conflict
6. After fixing the conflict, ran `git rebase --continue` and `git push` to finalize fix
