Here is the way to publish stuff to GitHub using Terminal:

1. Make a directory on the computer to store the repo
2. Clone the repo to the computer by going to "git clone http://##URL OF REPO HERE##"
^ You should only have to do that once I think
3. cd into the repo
4. Open a text editor and browse to the repo (folder with stuff) and from here you can start making files
5. Make a new branch by typing "git checkout -b BRANCH-NAME-HERE"
6. Do a "git status" to make sure you're on the right branch.
7. Work away in Sublime being cool af. Save it in the repo and remember the name.
8. "git status" will now show that there are new files.
9. Type "git add ##NAME OF THING AND PATH##" and hit enter.
10. Type "git commit -m "##DESCRIBE THE COMMIT##" and enter.
11. git push origin <!!branch name here!!!>
12. Should now be on GitHub.