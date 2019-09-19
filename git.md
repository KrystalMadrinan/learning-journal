# Git notes

### ***How to ACP***

- ACP stands for act, commit, push, and it's how we push changes from our local location back to GitHub (remote), using the terminal.
- First, clone your repo. Then make the changes you want in VS Code.
- Ready to ACP? Do these steps:
+ Make sure you're in the right directory. If not, use cd.
+ git status
+ git add filename (should be the ones in red) one at a time.
+ Those files should be green now.
+ git commit -m "Insert message here, why are you committing?"
+ git commit -a (saves changes)
+ Finally, git push origin master
- Double check in your remote location (Github) that the commit was successful. The terminal should tell you so with the blob of text after the last command.



### ***About Git: Intro Version - some notes***
- *VCS (Version Control System) - a system that lets you see different versions of a certain file through recording changes.
- Git helps greatly with file corruption and lost.
- Three states: committed, modified, staged ()
- Git needs to be downloaded and configurated, which you have done so already. Update when needed.
+ CLONING: git clone insert-clone-link-from-github repo-here
- ACP is possible through Git. 
- **Refer back to Git Intro article for a refresher or if you forget**



#### ***Helpful Resources***
- Lecture
- Class Repo
- Google everything git and terminal
- [Git intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)