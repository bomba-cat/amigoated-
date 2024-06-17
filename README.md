# How to Git >.<

## Common Commands
- `git init`, initialize a git repo
- `git commit -m "message" --all|files`, commit current stage
- `git add --all|files`, add files to the track
- `git reset HEAD~backwards count`, revert back 2 commits
- `git branch -D <branch>`, create a branch
- `git push`, push to a repo not locally
- `git clone repo`, clone a repo
- `git pull`, pull the latest changes
- `git checkout`, change branch
- `git origin set origin`, set origin

## Using git

### Initialize a git repo
- `git init`
This will create the base of the repository

### Add all files to the git repo
- `git add --all|files`
Now git will track all your files :D

### Configure the user and email
- `git config --global user.email "your.email@email.com"`
- `git config --global user.name "your username"`
now git knows your username and email so people can see who did that commit

### Commit all files to the git repo
- `git commit -m "message" --all|files`
Now we created a snapshot of our current state, we can start working on it.

### How do i revert to the last second commits !?
- `git reset HEAD~2`
Now you're set 2 commits back

### I want one branch where the developers work, and one branch where the designers work? How?
- `git branch -D developer`
- `git branch -D designer`
Now the designers can set their branch to the designer one and the dev's to the developer one like this:
- `git checkout developer`
- `git checkout designer`
