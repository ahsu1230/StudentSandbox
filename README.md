# StudentSandbox

A sandbox repo for students to practice using Git and Github.

## Objective

In this mini-project, we will go through the fundamentals of using Git and Github. We will learn to contribute to an existing code repository through both the Github website portal and from your command line with git. Follow the [sandbox development guide](./guide/00_intro.md) to start practicing with Github!

---

## Introduction Videos about Git

 - Intro to Git and Github: https://www.youtube.com/watch?v=r50BKIFGCI0
 - Creating your own Repository: https://www.youtube.com/watch?v=hMfi_ONvGEs
 - Branching: https://www.youtube.com/watch?v=iJKIxrJ40ss&t=9s
 - Pull Requests: https://www.youtube.com/watch?v=nT8KGYVurIU&t=5s
 - Installing Git:
   - Mac: https://www.youtube.com/watch?v=YXXp_ht4pwQ
   - Windows: https://www.youtube.com/watch?v=O72FWNeO-xY
 - Git Command Line commands: <https://www.youtube.com/watch?v=eL_0Ok_Gkas>

## **Basic Git Commands to use:**

  - **Creating and Switching branches:**

Creates a new branch of the name you input
```
git branch --create NEW_BRANCH_NAME
```
Lets you see how many branches there are
```
git branch 
```
Switches from your current branch to the desired branch
```
git checkout BRANCH_NAME
```
  - **Status, Add, Commit and Push**
  
"status" - Lets you see which changes have been staged, which haven't, and which files aren't being tracked
```
git status
```
"add" - Tells Git that you want to include updates to a particular file in the next commit
```
git add FILE_NAME
```
"commit" - Creates a new commit containing the current contents of the index and the given log message describing the changes
```
git commit -m "My First Commit Message"
```
"push" - Used to upload local repository content to a remote repository.
```
git push origin NAME_OF_BRANCH
```

  - **Other Commands that are Useful**
"help <verb>" or < "<verb> --help" - a list of the most commonly used git commands are printed on the standard output 
```
git <verb> --help
      or
git help <verb>
```

## Directions
 - Clone this repo to your local computer.
 - Create a local branch (`git branch`)
 - Make changes to the `index.html` file. Simply add a line like this: 
 ```
  <li> Pikachu was here! </li> 
 ```
Add the line inside the `<ul>` tags and beneath the previous person.

 - Add and push your changes (`git add` and `git commit` and `git push`)
 - Once your changes are pushed to a remote branch, follow the below directions to create a pull request.

## Creating a Pull Request

Once your changes are pushed, come to this Github repo website and look for the Branches tab. You should see your branch and there should be a "Create Pull Request" button next to your branch.
Once a Pull Request is created, tag me using @ahsu1230 to notify me that this pull request has been created.
When I give the go ahead, merge your changes and now your code will be part of this repo!

Congrats on finishing your first Git Pull Request!
