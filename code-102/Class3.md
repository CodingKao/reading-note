# Class 3 Notes 

# Revisions and the Cloud

#### Link to article: [Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

***

**What is Version Control?**
>Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified

**What is cloning in Git?**
>You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL
By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

**What is the command to track and stage files?**
>Single File
>
>Track one file only by using the following format:
>
    git add filename
>
>
>All Files
>
>Track all files in a repository by using the following command:
>
    git add *


**What is the command to take a snapshot of your changed files?**
>    
    git status
>
>This information tells us that there are changes to be committed and that the file has been staged.


**What is the command to send your changed files to Github?**
> The command to send your changed files to Github is:
>
    git push origin main
>
> This command pushes changes from the local “main” branch to the remote repository named “origin”.
