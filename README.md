# delta-demo
This is demo for Git &amp; Github class.
# Git - Git is a free and open source version control system tools that helps to tracks changes in code and collaborate.
1.track history
2.help to collaborate

# Github - website where we host repositories online

# README.md - The README.md file provides a detailed description of the project, including its purpose, how to set it up, and how to use it. It helps in effectively conveying the project's goals, setup instructions, and usage examples, ensuring that both contributors and users can engage with the project effectively.

# Git Commit - A Git commit is like a snapshot of your project at a specific point in time.
 Track Changes: Keep a record of what changes were made, who made them, and when.
 Collaborate: Work seamlessly with other developers without overwriting each other’s work.
 Revert Changes: Roll back to previous versions if something goes wrong.

Using Git with the help of ---
1.command line
2.code editors using extensions
3.graphical user interface

# Configuring Git - detailed stores in a git
git config --global user.name "Kajal Gupta"
git config --global user.email "kk2347994@gmail.com"

global means hm apni system ke andr jitni v jgh, git use kr rhe hai wha pr hm yhi email id aur yhi naam rkhna chahte hai.

# Basic Command:-

# Clone Command - The git clone command is used to create a copy of an existing Git repository. This command is essential for developers who want to work on a project hosted in a remote repository. The clone operation creates a new directory, initializes a new Git repository, and copies all the data from the specified repository into the new directory.

# status Command - The git status command is used to display the state of the working directory and the staging area. It shows which changes have been staged, which haven't, and which files aren't being tracked by Git. This command is essential for understanding the current state of your repository before making a commit.

1.tracked - tracked files are files that Git knows about.
2.untracked - untracked files are everything else — any files in your working directory that were not in your last snapshot and are not in your staging area. When you first clone a repository, all of your files will be tracked and unmodified because Git just checked them out and you haven’t edited anything.
3.modified - As you edit files, Git sees them as modified, because you’ve changed them since your last commit. As you work, you selectively stage these modified files and then commit all those staged changes, and the cycle repeats.

# Add Command - The git add command adds new or changed files in your working directory to the Git staging area. git add is an important command – without it, no git commit would ever do anything. 

modified -> add -> staged -> commit

# Commit Command -The git commit command is used to save changes to the local repository. Each commit represents a snapshot of the project at a specific point in time, allowing you to track and manage changes effectively. Commits include metadata such as the author, timestamp, and a message describing the changes.

# push Command - Git push allows us to transfer files from the local repository to remote repository hosting services like GitHub, GitLab, etc. Other developers who want to work on the files can access them after being uploaded to a remote repository.

origin means vo location jha github ki repo hai.

# init Command - The git init command is used to create a new Git repository. 