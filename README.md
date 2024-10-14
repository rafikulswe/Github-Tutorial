Topics of Github Tutorial 
1. How to create a github repository in online and how to work in this repository.
2. How to create a local repository and how to upload it to online.
3. How to create a branch in your repository and how to merge this branch.
4. Some Additional command- check different between two commit ID, Remove file, For reset, Back to first Stage etc.

# Git and Shell Command Reference

### `pwd`
Displays the present working directory.

```html
<div>
  <code>pwd</code>
  <button onclick="navigator.clipboard.writeText('pwd')">Copy</button>
</div>

### `pwd`
Displays the present working directory.

### `ls -a`
Lists all files, including hidden ones.

### `git status`
Checks the current status of your git repository, showing any changes staged for commit, files that aren’t tracked, and those with modifications.

### `git add .`
Stages all changes in the current directory.

### `git commit -m "conversational message"`
Records a commit with a message describing the changes.

### `git log` or `git log --oneline`
Displays the commit history. `git log --oneline` shows each commit on a single line for a more compact view.

### `git reset --hard <commitId>`
Resets the repository to the specified commit. It can be used to go back or forward in the commit history.

### `git reflog`
Shows a list of all activities including commits that may not be visible in the standard git log, such as resets and checkouts.

### `git rm <fileName>`
Removes a file and stages it for deletion in the next commit.

### `git branch --list`
Lists all branches in the repository.

### `git branch features/example-crud`
Creates a new branch named `features/example-crud`.

### `git switch features/example-crud`
Switches to the branch `features/example-crud`.

### `git merge features/example-crud`
Merges the branch `features/example-crud` into the current branch. You need to switch to the main branch first before merging.

### `git branch -d features/example-crud`
Deletes the branch `features/example-crud`, but only if there are no uncommitted changes.

### `git branch -D features/example-crud`
Forces the deletion of the branch `features/example-crud` without checking for uncommitted changes.

### `git branch -m dev/example-crud`
Renames the current branch to `dev/example-crud`.

### `git commit`
After resolving conflicts, this command can be used to commit with Git’s default commit message.

### `git stash`
Saves your uncommitted changes and clears the working directory, allowing you to switch branches without committing.

### `git stash list`
Displays a list of all stashed changes.

### `git stash show -p`
Shows the changes of a specific stash.

### `git stash apply <stashId>`
Applies the stash with the given ID to your working directory.

### `git stash pop`
Applies the most recent stash and removes it from the stash list.

### `git rm --cached <fileName.txt>`
Stops tracking the specified file without deleting it from the working directory, often used when adding files to `.gitignore`.

### `git diff <fileName.txt>`
Displays the changes made to the specified file.

### `git remote add origin <repo_link>`
Connects your local repository to a remote GitHub repository.

### `git push`
Pushes your committed changes to the remote repository.

### `git pull`
Pulls the latest changes from the specified branch of the remote repository.

### `git clone <repository_link>`
Clones a remote repository to your local machine.

### Connecting GitHub using SSH

#### `ssh-keygen -o -t rsa -C "github_email"`
Generates an SSH key. After generating the key, add it to your GitHub account under **Settings** -> **SSH and GPG keys** to enable SSH-based access to your repository.
