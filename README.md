# Pushing Projects
Reminder of how to push existing projects to GitHub through git bash

## On GitHub
1. Create github repository (uncheck create README.md since we're pushing project)
2. Keep open page that has GitHub repository on browser `e.g. https://github.com/[user]/[project].git`

## Git Bash Commands
1. Open git bash
2. Navigate to project folder through git bash (replace `\` with `/` if copying directory from File Explorer)
3. Type `git init` to initialise git repository
4. Add all files to Git index using `git add -A` 
5. Add commit comment using `git commit -m '[message here]'`
6. Add new remote origin (where to push project) using `git remote add origin [GitHub repository]`
7. Push files to GitHub repository using `git push -u -f origin master` (may need to enter GitHub credentials in order to push)

Refresh GitHub repository page and the project files should be pushed
