# Git-and-Github

**GIT** is a software and **GIT HUB** is a service provider. There are many service providers like github. 

**Version control system** tracks the files for changes

**Commit** is like a check point

`git init` : Intializes the git software.
   - This lets the current directory to be tracked by git.
   - This command is run once in the project directorty and the intialization happens. You don't need to run it again.
   - A hidden folder **.git** gets created to keep history of all the files and folders.
 
   
`git status` : To check the status of the git software.


![github_flow](https://github.com/user-attachments/assets/ec6556c6-39b6-4b1f-8ea1-6b24bacca25e)

**Staging area** is like a intermediate stage before you make any commit. 

**WRITE ADD COMMIT** is the flow

`git add <files>` : Moves the untracked files to the staging area. 
- To add all the files no matter what, you can do `git add .` 
 
`git commit -m <message>` : To commit the files that are in the staging area.
- Commit needs a message.
- If commit message is not provided, a vim code editor will be opened and you have to write a message there.

`git log` : Gives the details of commit ID, Author, date and time of commit, commit message. 
- Each commit ID is differentiated by the initial few characters (SHA)
 `git log --oneline` : Less detailed

#### Atomic Commits (How to write a commit message?)
- Keep commits centric to one feature or fix. Focus on one thing.
- Present tense and Imperative (Command)

A **Git configuration file** stores settings that control Git’s behavior for a user, repository, or system.

#### Types of Git Configurations:
- System-wide (**/etc/gitconfig**) - Applies to all users on the system
- User-level (**~/.gitconfig** or **~/.config/git/config**) - Applies to a specific user
- Repository-specific (**.git/config** inside a repo) - Affects only that repo

#### Common Commands
- View config : `git config --list`
- Set username : `git config --global user.name "Your name"`
- Set email : `git config --global user.email "you@example.com"`

