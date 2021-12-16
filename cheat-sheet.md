## What is the Terminal & Command Line?

The **command line** is a text-based interface that allows you to enact changes to your computer's files and much more!

Some basic commands:
- **cd**: Changes the directory to a specified directory. For example: `cd ~/CodeFellows/course/`
- **mkdir**: Creates a new directory. For example: `mkdir ./codeFellows/course/course-101/`
- **pwd**: Outputs your working directory (the directory you are currently in). For example: `pwd` output: `Users/Jake/Codefellows/course`
- **ls**: Lists the files of your current directory. For example: `ls will show files such as course 102 within your course folder.

**cd**: In order to navigate the file system using the command line, you will need to use `cd`. The syntax can be tricky at first. The basic syntax is `cd /folder-name/`. However, the location is relative. This means that `cd` will assume that the directory you are changing to exists within the same directory you are currently in. The way around this is using absolute paths. For example, if I am currently in `/projects/courses/courses/course-102` and I wanted to move to a folder in the home directory, I would have to type `cd /~/other-folder/`. Below are some more examples of how to use it:
- `cd ./projects/courses`: Sets your working directory to `/courses/`. 
- `cd ..` : Sets your working directory to the directory above it. For example if you are in `/folder/courses/`, entering `cd ..` will cause your working directory to change to `/folder/`. 

