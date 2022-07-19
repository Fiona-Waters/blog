---
slug: git-beginner
title: Git - Not another tutorial!
authors:
  name: Fiona Waters
  image_url: https://avatars.githubusercontent.com/u/76408967?s=40&v=4 
tags: [git]
---
 
“Oh no”, I hear you say, “not ANOTHER Git tutorial!” Well you can breathe a sigh of relief, because this is not another Git tutorial. It’s not even close! The only way I would be able to write a Git tutorial would be if I really understood Git and what commands I want to use each time I open a terminal window. Unfortunately this is not yet the case.

So if this is not a Git tutorial then what is it? This is a beginners guide to Git commands. Since starting my internship at Red Hat, just one month ago, I have realised the significance of Git. To be able to complete almost any task in a software engineering related role Git is a must. There is very little you can do (safely) without it. So with Git beginners in mind (like myself) I will run through the most common Git commands I have come across over the past month and hopefully in doing so will help myself to understand Git better and maybe pass on a tiny bit of info to anyone else that might be interested.

![computer](./pexels-soumil-kumar-735911.jpg)

Let’s start by quickly explaining what Git is!
In simple terms Git is a version control system. It allows you to keep track of any changes you make to your code. It can be used on the smallest project with just one developer, or on the largest project with many developers.
Another important attribute of Git is that it is Open Source, and in fact was originally developed by Linus Torvalds, the creator of the Linux kernel.

Disclaimer!
The following information is my understanding of these commands based on my use of Git so far on my software engineering journey. There are many Git tutorials and places online to get info. The one I have found most useful is [Atlassian](https://www.atlassian.com/git/tutorials). To get all of the details from the experts check them out.

## The Commands
Right, let's get to it…

### git status
This command is of great importance and it does what it says, checks the current status! It will show you what files have been changed and if the changed files have been staged or not. From here you can decide if you want to add them to the staging area. This should be used often, and in between other commands!

### git add
This command allows you to add files to the staging area, ready to commit them to your local repository.  The staging area shows files selected to be included in the next commit.

### git commit
This command creates a representation of the current state of the project at the current time. For me this occurs at a natural stopping point, where you want to save your work and be able to come back to this point if you need to. This can be especially useful if you make any mistakes along the way - you know that you can go back to a point before the mistake was made and start again from there.

### git push
This command allows you to send the local copy of your repo to a remote repo. These remote repositories are usually found online. There are many products offered in this area with [GitHub](https://github.com/) and [Bitbucket](https://bitbucket.org/) being 2 of the most popular.

### git pull
This command will update your local repository with any changes made on the remote repository. This is used when more than one person is using the repository. I never used this command when working on college projects alone but have used it during my internship when using a repo that is worked on by many others.

![learn](./pexels-pixabay-247819.jpg)
### In Conclusion
These commands have many options other than their basic use. You can look at them in more detail in the [Git](https://git-scm.com/docs) documentation.

These are just a few of the commands I have used so far and are the ones I feel most confident talking about. I have used loads more, some of which I am terrified by but I am hoping that I will master them over time! Wish me luck…


 
