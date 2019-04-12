# The Challenge
___
The purpose of this project is to help you familiarize yourself with basic git commands. This will teach you the basics of managing a project via the command line. You will learn how to create repositories, create branches, merge pull requests. Repeat these Parts as many times as necessary, adding any files you want, changing your own files, etc to watch how things change. keep your github account open in a browser window and refresh often so you can watch the changes you make. Repeat this as many times as you want to learn these commands and how they function. 

You will be using the commands on this simple git guide to complete the following tasks. I've included certain phrasing to hint at the commands you will need at each step and there's a very brief glossary at the end. 

http://rogerdudler.github.io/git-guide/



Git should already be installed and configured on your computer. Please follow the instructions on the simple guide to do so if you have not.


___

### Part 1: Creating a new project
1. Create a new folder on your desktop. Name is anything you'd like, no spaces.
2. Create a text file in this folder, give it any content you want but make sure to save the file as README.MD
3. README.MD is the default file for a repository on Github, so when you go to that project on your account this is what will be listed as the description.
4. Open your command line (Terminal on a Mac, Git Bash on Windows) and browse to the folder on your desktop. the easiest way to do this is typing "cd" in your command line and then dragging the folder you made on your desktop over the command line to create a link to the folder. Hit enter to browse to that directory
5. Create a repository in this folder. This is the first version of this project. 
6. Add all the files in this folder to the repository
7. Commit the files to the repository. Make sure you include a commit message
8. Push these changes to github

### Part 2: Creating a branch
9. You have the first version of your project. now it's time to make changes. Create a new branch.
10. Create another text file in your project folder. Name it anything you want, add any content you want. alternatively, you could edit your README.MD file. Either of these is fine. 
11. Add these updates/created files to your repository.
12. Commit these files.
13. Push these changes

### Part 3: Merging your branch
14. Go to your account on github, this is http://github.com/YOUR_USER_NAME
15. Click on your now pushed project. You'll see there are two branches you can select on this project. Open the one you just made.
16. Click on the open pull request button
17. Select "compare: your branch" to "base:master"
18. Click on create pull request. This will allow you to merge the new branch into the first version you create in Part 1. 
19. Approve your own pull request. 
20. Your github project will show you have merged the two branches. 
21. Sync up your local copy of this project by going back to the command line and pulling the update





___



##### Quick Glossary:


|  |  |
| ------ | ------ |
| Project | this is a project you're working on. pretty straight forward |
| Repository | this is your file on github. It is basically your project, along with each version of the project you make. it allows you keep track of changes to your project. |
| Add | in order for your to track changes to files in your project, you have to add them to your repository.  |
| Commit | if you make show a file has changed, you have to acknowledge you made a change to a file |
| Push | when you move changes to your github repository, you are "pushing" those changes to the server |
| .MD | this is short for Markdown, a simple stylized text format https://en.wikipedia.org/wiki/Markdown |
| Pull | if you or someone else made changes to the project, you can add those changes to your local copy of the project by "pulling" them from the server |
| Command line | this has a lot of names. DOS Prompt, Bash, Terminal, etc.  |
| Branch | If you are making a lot of changes to your project, instead of adding things to your main/master project, you can create a branch of it and make changes there.  |
| Merge | if you feel like these changes you made via a branch can become the main project, you can "merge" them together |
| Trunk | there's a lot of tree terminology in file structures, right down to being called a "file tree". the primary version of your project is the trunk, versions you're working on that you don't want to be part of the trunk are branches. |
