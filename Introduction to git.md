# Intoduction to VScode, Git and Github

## What is VS Code?
Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages and runtimes (such as C++, C#, Java, Python, PHP, Go, .NET)

### The extensions
VScode is more than just an IDE, it is aiming to be a one stop shop for developers, including terminal (command line), jupyter notebooks, dockerfiles, remote connections, git etc.

Before starting, here are some very useful extensions worth installing:

Jupyter `ms-toolsai.jupyter` <br>
Git graph `mhutchie.git-graph`<br>
Python `ms-python.python`<br>
Remote SSH `ms-vscode-remote.remote-ssh`<br>
Jupyter Notebook Renderer `ms-toolsai.jupyter-renderers` <br>
Excel Viewer `GrapeCity.gc-excelviewer`<br>
Docker `ms-azuretools.vscode-docker`<br>

Using that you will probably won't leave VScode (unless you want to take a break)

## What is git?

Git a version control system.
version control system allows us to track the changes in our code over time in a database called repository. Using git we see who changed the files, when, and what.
It is actually preventing our folders to look like that:
- "project"
- "project_sofi"
- "project_sofi_sofi"
- "project_sofi_sofi_final_no_more_changes"
- "project_sofi_sofi_final_no_more_changes_ok_one more"

There are two different types of version control systems:
### <b>Centrilized</b>
Google sheets, for example.

### <b>Distributed</b>

In distributed each colaborator has his own copy in the machine, using smart "pull-push" technique to make sure everyone is aligned.

## Installing git.
Just go to https://git-scm.com/downloads and download it.

## Configuration:
We have 3 different levels of cofigurations
1. System - For all users in the machine
2. Global - For all repositories of the current user, this will be used most of the times.
3. Local - for the current repository. 

## Initializing a git repo.
In the terminal - run the command git init<br>
In VS code - Go to the source control tab and press initiate git.<br>

It will create a new subfolder called .git (You can't see it and you shouldn't modify it) that marks your folder as a "git repository". From now on all git commands are open for that folder.


## The standard git workflow:

![The git workflow](images/github_workflow_1.jpg)

In git we have 3 areas:
1. **The ordinary folder** - This is what everyone is using. 
2. **The staging area** - The "pre-commit" stage, this is where you review the code. we use the command `add` to add new files.
3. **The repository.** - The code repository. we can move files from the staging area to the repository. The snapshots are saved there. We use the command `commit` to move all files from staging area to the repository.

Let's see a demo.

## Using it with VScode.
After installing vscode and its extensions, it will be much easier to view and working with Git. Now you have a good visualization on the staged files.

## Branching and checkout
While developing a new feature or we want to go to a current direction, we can branch our progress to "a new path", where we can always revert to the where we splitted. It is a good practice where you don't know whether your work is going to be useful or not. This is called branching and can be done by the command `git branch`

## Adding your code to github.

### First thing first
<b>What is the difference between Git and Github?:</b>
<br> 

> As the same difference between XXXX and XXXXhub.

In other words, Github is where you store your gits. Github can be used as a portfolio, hosting open sources, storing the codebase of companies etc. 

After working on a long project and you want to show it to the world, so your Github is your first go to.<br>
The process is quite easy.

1. Sign up.
2. Push your git to github.