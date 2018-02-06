# BIOL 812 Assignment - Create a GitHub Pages Website

## By Kurtis Westbury

Some information on Git and GitHub that may be useful for your project.

### 1. When should you use Git for a project?

Great question, Git is a useful system for storing and working with data that is different from most other cluster servers. Instead of looking at data as a file, Git will look at data as a series of snapshots that are compacted in a filing system. The snapshots, known as commits are different than usual changes to data because you can access your history, therefore you can not make a permanent accidental change in your data.

GitHub is the web service for version control using Git. This website is useful when working with multiple collaborators on a project using Git. With GitHub, a collaborator could make a commit on one of your respositories, and these changes would not happen unless approved by the creator of that repository.

### 2. What kind of files/info should be saved in a Git repository? What types of files/info should not be included in a Git repo?

Git repositories should be used to store codes, scripts, any text-based files. Since Git is a public database, it is not advised to store large datasets or confidential information in a Git repository.

### 3. What are the commands to undo a commit?

To undo a commit at the command line using Git, use the command:

```git checkout HEAD~1 <filename>
```
