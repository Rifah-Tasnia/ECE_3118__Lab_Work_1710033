# Git Initialization

To implement version control in a folder we need to write follwing command 

```
$ git init 
```

# Staging a file

To add a file before commit <br>
**add** changes from all tracked and untracked files
```
$ git add -A
```
 

# Git Commit
It is used to record the changes in the repository. It is the next command after the **git add**.
```
$ git commit 
```

# To update tracked files

```
$ git -u
```

# Git Clone Command
The **git clone** is a command-line utility which is used to make a local copy of a remote repository. It accesses the repository through a remote URL.
```
$ git clone <repository URL>  
```


# Cloning a Repository into a Specific Local Folder
 Git allows cloning the repository into a specific directory without switching to that particular directory. You can specify that directory as the next command-line argument in git clone command. See the below command:

 ```
$ git clone https://github.com/ImDwivedi1/Git-Example.git "Folder_name"  
```