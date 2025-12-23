# meta-version-control-forking-lab

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Learning Objectives
for the meta-version-control-forking-lab

github repository
how to use flags

-a --all  used to show all branches
-b --branch  used to create a new branch
-d --delete  used to delete a branch
-m --move  used to rename a branch
-l --list  used to list branches
-L --list-all  used to list all branches
-A --abbreviated  used to show abbreviated commit hashes
-u --untracked-files  used to show untracked files in the working directory
-w --word-diff  used to show word-level differences between files
-la --log-all  used to show the commit history for all branches
-lh --log-honest  used to show the commit history with honest formatting
-pwd  --patch-with-stat  used to show changes with path information
-wc  --word-diff=color  used to show word-level differences with color highlighting
-v --verbose  used to show more detailed information
-q --quiet  used to suppress output
-f --force  used to force an action
-p --patch  used to interactively select hunks of changes to commit
--stat  used to show statistics about changes
--graph  used to show a graphical representation of the commit history
--decorate  used to show branch and tag names alongside commit hashes
--set-upstream  used to set the upstream branch for the current branch
--no-ff  used to create a merge commit even if the merge could be resolved as a fast-forward
--squash  used to combine multiple commits into a single commit
--amend  used to modify the most recent commit
.bashrc file
aliases
git lg='git log --oneline --graph --decorate --all'
git st='git status'
git co='git checkout'
git br='git branch -a'
git df='git diff'
git cm='git commit -m'
git pl='git pull'
git ps='git push'
git rb='git rebase'
git mg='git merge'
git unstage='git reset HEAD --'
git last='git log -1 HEAD'
git amend='git commit --amend'
git wipe='git reset --hard HEAD && git clean -f'
git tags='git tag -l'
git show-branch='git show-branch --all'


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Key Terms
forking
clone
pull request
upstream repository
downstream repository
branch
merge
conflict
commit
push
pull    

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

some useful commands
git fork <repository-url>  # Fork a repository
git clone <forked-repo-url>  # Clone your forked repository to your local machine
git remote add upstream <original-repo-url>  # Add the original repository as an upstream remote
git fetch upstream  # Fetch changes from the upstream repository
git checkout main  # Switch to your local main branch
git merge upstream/main  # Merge changes from the upstream main branch into your local main branch
git push origin main  # Push the updated main branch to your forked repository
git checkout -b <new-branch-name>  # Create and switch to a new branch
git add .  # Stage changes for commit
git commit -m "Your commit message"  # Commit your changes
git push origin <new-branch-name>  # Push your new branch to your forked repository
# Create a pull request on GitHub from your forked repository to the original repository
git diff  # Show changes between working directory and index
git log --oneline --graph --decorate  # Show a graphical representation of the commit history
git status  # Show the status of changes in the working directory
git branch -a  # List all branches, including remote branches
git merge <branch-name>  # Merge a branch into the current branch
git rebase <branch-name>  # Reapply commits on top of another base tip
git stash  # Temporarily save changes that are not ready to be committed
git stash pop  # Reapply stashed changes and remove them from the stash list
git reset --hard <commit-hash>  # Reset the current branch to a specific commit
git cherry-pick <commit-hash>  # Apply the changes introduced by an existing commit
git tag <tag-name>  # Create a new tag
git push origin <tag-name>  # Push a tag to the remote repository
git checkout <commit-hash>  # Switch to a specific commit
git reflog  # Show a log of all changes to the tip of branches and other references
git clean -f  # Remove untracked files from the working directory
git config --global user.name "Your Name"  # Set your Git username
git config --global user.email "your.email@example.com"  # Set your Git email
git help <command>  # Show help for a specific Git command
git blame <file>  # Show who made changes to each line of a file
git bisect start  # Start a binary search to find a bug
git bisect good <commit-hash>  # Mark a commit as good during bisect
git bisect bad <commit-hash>  # Mark a commit as bad during bisect
git bisect reset  # End the bisect session and return to the original HEAD
git diff HEAD~1 HEAD  # Show changes between the last two commits
