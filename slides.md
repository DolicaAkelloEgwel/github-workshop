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

Now to take a look at the folder we can go to the top menu and click Repository > Show in Finder / Explorer.

<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>


![bg right](./pictures/setup-in-desktop.PNG)

---
# Creating a Text File

Now let's create a simple text file and add two lines of text to it. This will cause a change to appear in GitHub Desktop.

If you're on Mac you can use `touch` to create an empty file.

---

![h:580 center](./pictures/diff-add.png)

---
# Commiting Files

1. Tick the checkbox next to the file you want to include in the next commit. This _stages_ the file.
2. Give a commit message. This should describe the changes that you have made to the file(s). You can also provide an optional description.
3. Click the blue Commit button. This will now create a new "snapshot" of our repository.

---
# History

Take a look at the History tab. You can now see the commit with its message. The right hand pane will show us what was changed in this commit.

---
# Diff View - Continued

Now delete the _second_ line of your file and see what happens in GitHub Desktop.

---
# How often to commit?

When it _feels right_...

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
# .gitignore

- A .gitignore file let's Git know that you don't want a certain file to be tracked with version control

---
# Exercise: Merge Conflicts

---

# Cool Git-Related Things

---
# The magic of `bisect`

`git bisect` is a handy command that can be a life-saver.

---
# Extra Extra: `pre-commit`

- `pre-commit` is a tool that ensures certain checks on your file pass before a commit is accepted.
- This could be a linting tool 

---
#  `lazygit`
---
# Keeping track of your essays with Git and LaTeX

![h:480 center](./pictures/dissertation-commit-log.PNG)

BTW these slides also live in GitHub...

