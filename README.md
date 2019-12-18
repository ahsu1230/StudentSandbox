# StudentSandbox
A sandbox repo for students to practice using Git and Github

Video of Command Line commands: <https://www.youtube.com/watch?v=eL_0Ok_Gkas>

## **Basic Command Line Operations:**

"cd" - Stands for Change Directory
```
cd @nextDirectory
```

"mkdir" - Makes a new Directory
```
mkdir @nameOfNewDirectory
```

"ls" - Lists all the files and directories
```
ls
```

## **Basic Git Commands to use:**

  - **Creating and Switching branches:**

Creates a new branch of the name you input
```
git branch --create '@nameOfBranch'
```
Lets you see how many branches there are
```
git branch 
```
Switches from your current branch to the desired branch
```
git checkout @nameOfBranch
```
  - **Status, Add, Commit and Push**
  
"status" - Lets you see which changes have been staged, which haven't, and which files aren't being tracked
```
git status
```
"add" - Tells Git that you want to include updates to a particular file in the next commit
```
git add @fileName
```
"commit" - Creates a new commit containing the current contents of the index and the given log message describing the changes
```
git commit -m '@text'
```
"push" - Used to upload local repository content to a remote repository.
```
git push origin @nameOfBranch
```
  - **Other Commands that are Useful**
"help <verb>" or < "<verb> --help" - a list of the most commonly used git commands are printed on the standard output 
```
git <verb> --help
      or
git help <verb>
```
