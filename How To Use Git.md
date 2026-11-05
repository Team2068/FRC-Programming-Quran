These are some very useful git commands that we use and help us work effectively as a team.

## Downloading Repos:
- `git clone` Clone is used to download a git repo onto your computer.
- `code .` After cloning a repo, use code . to open it in VS Code. (Not a git command but still very helpful)

## Pulling code changes:
Pulling code is when you download the most recent code changes from a remote repo.
- `git pull` Pulling the most recent code.
- `git stash` Stashes away uncommitted changes.
- `git stash pop` Restores your most recent stash.

### Pushing your code:
Pushing code is when you send your current code to GitHub. We do this in 3 steps.
1. `git add .` "Stages" changes to all files in your current directory. Staging means that you are marking certain files to be in your next commit. The `.` is to have it so all files in your current directory are staged and will be in your next commit. Alternatively you can use `-A` to mark your entire repo or the directory you want to stage.
2. `git commit -m "your message"` Creates a commit with your staged changes and your message.
3. `git push` Uploads commits to the remote repo.

### Branches:
We use branches to work on our code without affecting our main branch. Specifically, we use branches to work independently on different systems and features such as new subsystems or refactoring.
1. `git checkout -b <branch_name>` to create a new branch and switch to it.
2. `git checkout <branch_name>` to switch to a different branch.
3. `git branch` to see which branch you are currently on and a list of local branches.
#### Alternative to Checkout
You can also use git switch commands to switch and create branches.
1. `git switch -c <branch_name>` to create and switch to a new branch.
2. `git switch <branch_name>` to switch to another branch.

### Merging:
When merging 2 branches together you may run into merge conflicts. For merging you can either use the git terminal command or the Pull Requests section on GitHub. If there is not a merge conflict then git will automatically merge them.

1. `git merge <branch_name>` Merges the history and changes of a specific branch into the branch you are currently on.
2. `git pull origin main` Pulls the main branch from your remote and merges it into your currently checked out branch.


### Other Git Commands:
A lot of these are less important or you won't use as often as the commands above but they are still important.
`git init` creates a new local git repo.
`git config --global user.name "YourName"` changes your git author name.
`git config --global user.email "your@email.com"` changes your git author email.
`git remote add origin <url>` Links a local repo to a remote server.
`git fetch` Downloads the latest changes from remote without changing your local files.
`git status` Shows your current branch and which files have been modified, staged or untracked.
