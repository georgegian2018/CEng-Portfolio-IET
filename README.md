# 🛠️ Git and GitHub for Beginners Tutorial

In this step-by-step tutorial, learn how to use Git and GitHub for Source Control Management (SCM). 
We start with Git. What is it? How you can get it running on your system, and how you can start working with it? Then we look at GitHub.com, a platform for hosting and collaborating on Git repositories. By the end, you'll be well on your way to using Git and GitHub. If you'd like to follow along, I've included sample files down below.

## 📚 RESOURCES
- Sample files to follow along: 
- Official Git web site: https://www.git-scm.com/
- Official GitHub.com web site: https://github.com/
- Git and GitHub.com cheat sheet: https://education.github.com/git-cheat-sheet-education.pdf
- Git Reference Manual: http://git-scm.com/docs
- Git Overview Book: http://git-scm.com/book/en/v2
- Sample ignore files: https://github.com/github/gitignore
- Hyper.is Terminal: https://hyper.is/

## 🖥️ GIT COMMANDS CHEAT SHEET
**Set configuration values for your username and email**
```text
git config --global user.name YOUR NAME
git config --global user.email YOUR EMAIL
```

Set default branch to main
```text
git config --global init.default branch main
```

Get help on a command
```text
git help COMMAND
git COMMAND -h
```

Initialize a new git repository
```text
git init
```
Clone a repository

```text
git clone REPOSITORY URL
```

Add a file to the staging area
```text
git add FILE
```

Add all file changes to the staging area
```text
git add --all
git add -A
git add .
```

Check the unstaged changes
```text
git diff
```

Commit the staged changes
```text
git commit -m "MESSAGE"
```

Reset staging area to the last commit
```text
git reset
```

Check the state of the working directory and the staging area
```text
git status
```

Remove a file from the index and working directory
```text
git rm FILENAME
```

Rename a file
```text
git mv (OLD NAME) (NEW NAME)
```

List the commit history
```text
git log
```

List all the local branches
```text
git branch
```

Create a new branch
```text
git branch BRANCH NAME
```

Rename the current branch
```text
git branch -m NEW BRANCH NAME
```

Delete a branch
```text
git branch -d BRANCH NAME
```

Switch to another branch
```text
git switch BRANCH NAME
```

Merge specified branch into the current branch
```text
git merge BRANCH NAME
```

Create a connection to a remote repository
```text
git remote add (NAME) (REPOSITORY URL)
```

Push the committed changes to a remote directory
```text
git push (REMOTE) (BRANCH)
```

Download the content from a remote repository
```text
git pull REMOTE
```

 ~~📺 RELATED VIDEOS~~

 ~~🙌 SUPPORT THE CHANNEL~~

 ~~🔽 CONNECT WITH ME~~

 ~~🎒 MY COURSES~~

 ~~🙏 REQUEST VIDEOS~~

 ~~🔔 SUBSCRIBE ON YOUTUBE~~

# Basic writing and formatting syntax
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

---
## 📜 License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)](./LICENSE).

---

## 🙌 Acknowledgments

Built and maintained by [Georgios Giannakopoulos](https://github.com/georgiosgiannakopoulos).  
Inspired by open knowledge engineering and long-term documentation practices.
