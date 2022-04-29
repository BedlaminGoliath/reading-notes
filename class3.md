# Git with it
Git is a form of a VSC(version control system) which allows the user to revisit past versions of a file by taking a "snapshot" of previous saves, without mudding up the save folder. This helps a user back track to make changes to a earlier "save" or to revert back to the past snapshot all together, perhaps because it was better off before it "jumped the shark". Tnis feature is great help against a corrupt file messing up the file after a certain point, with Git the team (or individual) would be able to revert back prior to the problems focal point.

# 3 version controls:

- Local version control *saves versions on users hard disk* for singular use.

- Centralized Version Control *This allows team or group to view and edit a file and collaborate*

- Distributed Version Control *This version Mirrors a project across various repositories.This is also a safe way to fight against a single database being corrupted or going down which would make the project for all users not useable.


# Back story
The beginning of Git goes back to an open source project Linux kernal("The **Linux kernel** is the foundation of the Linux computer operating system. A kernel is the lowest level of software that can interface with computer hardware."[1^]).Git allowed support for large projects and "... Possessed strong  mechanisms preventing corruption...[2^])s. With this model in mind Git has become very popular.
unlike most installations everyone knows the easiest way to install Git is via the Terminal *see [chapter:2](class2.md)*

## Local Repository Structure

**Working Directory** :arrow_forward: **Index** :arrow_forward: **Index**


## Important commnands in the ACP process

There are various commands that can bet intered into the terminal, that can set up yout file to be handled in which ever way you see fit. there are 3 stages;
- Add: here you can enter ``git add filname`` to enter a specific file (or ``git add *`` to add all files)

- Commit: Here is where you commit the changes `` git commit`` and even leave notes stating those changes by using the `` -m`` at the end. `` git commit -m (message here)``

- Push: here is where you would push the file to a remote repo. `` git push origin master``
 the local branch is refered to as "master" and the remote branch os referred to as the "origin" (origin from which you cloned from). 
 
 
##### *resources*

[^1]: (https://blog.udemy.com/git-tutorial-a-comprehensive-guide)
[^2]: (https://blog.udemy.com/git-tutorial-a-comprehensive-guide)

  

## Thanks for coming to my Ted Talks, I Hope you liked it or whatever


![Lumpyspace princess](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse2.mm.bing.net%2Fth%3Fid%3DOIP.6PAncSKEhn0tqzgPGxRY1AAAAA%26pid%3DApi&f=1)
