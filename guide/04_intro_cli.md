# Introduction to Command Lines

Awesome! So we've created a Pull Request using the Github portal. However, it's not very convenient to modify multiple files using just the Github website portal. Your workflow would be much better if we downloaded the repo to our computers and worked from there.

But to do that, we'll need to learn how to use our computer's command shell program.

Most of the computer programs you've used would probably be considered GUIs (Graphical User Interfaces). These programs are usually programs that allow point & click interactions between the user and computer. For instance, to play music from Spotify or iTunes, you would click around the music library, select a song, and click play.

There are a couple of programs that don't have GUIs and instead, are considered CLIs (Command Line Interfaces). CLIs are programs that prompt users to type in commands for the computer to execute. They usually look very "primitive" and are mostly used for more basic functionalities. However, because of their simplicity, they can actually perform tasks much faster than the GUIs.

## Example of a CLI program

Let's say I need to get to the `Desktop/MyPictures/TokyoOlympics2020` folder on my computer. With Finder (Mac) or Explorer (Windows), we simply click on the Desktop folder, then click on MyPictures, then click on TokyoOlympics2020. Pretty simple, but takes a few steps.

With a Command Line program, you simply input:

```unix
cd /Desktop/MyPictures/TokyoOlympics2020
```

and you immediately traverse to the target directory (a.k.a folder) without having to go through the multiple steps as you would in the GUI. CLIs are not as intuitive to use as GUIs, but once you know how to get around the command line programs, you'll find yourself unlocking a new found power :).

CLI programs also differ between operating systems.

- If you have a Mac, your software of choice would be Terminal
- If you have Windows, your software would be Command Prompt.

## Terminal (MacOS)

Take a look at this video: <https://www.youtube.com/watch?v=5XgBd6rjuDQ>

You want to know how to use the following commands:

- `pwd` Print Work Directory
- `ls` Print all files in directory
  - `ls -l` Prints all files with detailed information
- `cd` Change Directory
  - `cd ..` To go the Parent Directory (back one level)
- `mkdir` Make Directory
- `cp` Copy File/Directory
- `mv` Move File/Directory
- `rm` Deletes a File
  - `rm -r` Deletes a Directory
- `cat` Prints contents of a file
- `echo` Print something!
- CTRL+C to quit out of a program that's running

Google any of these commands to see how to use them! Each of these commands can often have many different options. You don't have to know all of them, but it's good to get into the habit of Googling for more information.

## Command Prompt (Windows)

Take a look at these videos:

- <https://www.youtube.com/watch?v=MBBWVgE0ewk>
- <https://www.youtube.com/watch?v=7ABkcHLdG_A>

You want to know how to use the following commands:

- `cd` Change Directory
  - `cd ..` To go the Parent Directory (back one level)
- `dir` Print all files in directory
- `mkdir` Create a new directory
- `copy` Copies a file from one location to another
- `del` Deletes one or more files
- `echo` Display a message!

Google any of these commands to see how to use them! Each of these commands can often have many different options. You don't have to know all of them, but it's good to get into the habit of Googling for more information.

---

[Continue](./05_install_git.md)
