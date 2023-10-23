---
marp: true
---
# Introduction to GitHub and Version Control

---
# What is Version Control?

- A better kind of backup
- Review history of your changes
- Restore older code versions
- Undo mistakes
- Maintain several versions of your code at the same time

---
# What is Git and GitHub?

Git: Version control tool to manage code history
GitHub: Hosting service for Git repositories

---
# Creating a Repo

1. Go to GitHub.com and make sure you're logged in
2. Click on the green button that says New
3. Give the repo a name and a description
4. Make the repo public
5. Click on Create Repository

---
# Configure GitHub Desktop

Now that we've created a repo we can use GitHub Desktop to open it.

1. Click "Set up in Desktop"
2. Choose a local path for the repo
3. Click "Clone"

Now to take a look at the folder we can go to Repository > Open in Explorer.
---
# Creating a Text File

Now let's create a simple text file and add something to it. This will cause a change to appear in GitHub Desktop.

---
# Diff

When a line has been added to a file since the last commit, it will appear in green. When a line has been removed, it will appear as red. This `diff` view shows us how a file has changed. In this case, we will have just one green line to indicate that text has been added.

- `add` - _Stages_ a file, meaning that it will be included in our next commit.
- `commit` - Save the _staged_ changes that we created with `add` into a new commit. This then becomes a snapshot of the state of our code at a particular time.

---
# Git Log

Now we can take a look at our History tab and see the change.

- `amend` - Sometimes you make mistakes in your commit message. This allows us to fix them.
- `push` - Allows us to upload commits to our repository on GitHub.

---
# Committing Multiple Files

- Sometimes multiple files have changes. This can be seen when you use the `git status` command, or by looking at the changes menu in GitHub Desktop.
- Git allows us to choose which files will be in a single commit. This allows us to keep things more organised.

---
# Git Magic: `bisect`

`git bisect` is a handy command that can be a life-saver.

---
# lazygit
