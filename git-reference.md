# Git Reference
## Configuration
`git config --global user.name "Your Name"`
Sets the name associated with your Git commits.
`git config --global user.email "your@email.com"`
Sets the email associated with your Git commits.
## Repository Commands
`git clone <repository-url>`
Creates a local copy of a remote repository.
`git status`
Shows the current state of the working directory and staging area.
`git add <file>`
Stages a specific file for the next commit.
`git add .`
Stages all changed files in the current repository.
`git commit -m "message"`
Creates a commit with a descriptive message.
`git log --oneline`
Displays a simplified version of the commit history.
`git push`
Uploads local commits to the remote GitHub repository.
`git pull`
Downloads and integrates changes from the remote repository.
## Helpful Workflow
1. Make changes to files.
2. Run `git status`.
3. Stage changes with `git add`.
4. Commit changes with `git commit -m "message"`.
5. Push commits with `git push`.