# Installing Git

Now that you know how to use a Command Line interface, it's time to install and use Git!

## Install Git on Mac

<https://www.atlassian.com/git/tutorials/install-git#mac-os-x>

*Note* If you are on an old MacOS version or the above doesn't work, you can install Git using [Homebrew](https://brew.sh/). Open Terminal on your Mac and input the line you see on the *Install Homebrew* page. The script will pause to wait for your confirmations. Simply follow the directions to correctly install Homebrew, which will also install XCode and Git. If Terminal, verify that git installed correctly using `git --version`. If it is still not available, use the command `brew install git`.

## Install Git Windows

<https://www.atlassian.com/git/tutorials/install-git#windows>

## Verify Git Installed

Open up Terminal / Command Prompt and input the following command (from any directory):

```unix
git --version
```

This will display the version number of git installed on your computer. If this command does not work, you may have to close Terminal / Command Prompt and try this command again. If it still doesn't work, you may have to retry the install process.

## Configure Git

Once you've confirmed that Git has installed correctly. Configure your git using the following two commands. Make sure the email you use here matches the email you used to sign up for Github in an earlier step.

```unix
git config --global user.name "Emma Paris"
git config --global user.email "eparis@atlassian.com"
```

---

[Continue](./06_git_cli.md)
