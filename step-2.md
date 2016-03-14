# Step 2

### Initialize, add, and commit
- Head over to your command line and run these commands.
```
$ mkdir "[the name of your repository]"
$ cd "[the name of your repository]"
$ echo "# something cool here" >> README.md
$ git init
$ git add .
$ git commit -m "[write a message here]"
```
- *What's going on??*
  - `mkdir` creates a new directory with a specified name
  - `cd` changes directories and goes into the directory of the specified name
  - The third line creates a new file called `README.md` and enters "# something cool here" in it
  - `git init` creates a local repository in the directory you're in
  - `git add .` adds all the files in the directory to your repo
  - `git commit -m "first commit"` commits the changes you made locally

### Remotes and push!
- Next, look for something which says `Quick setup - if you've done this kind of thing before` 
- Under that, you'll see a two buttons which say `HTTPS` and `SSH`. Make sure `SSH` is selected
- Next, copy the link next to it
- Go back to your command line and run the following
```
$ git remote add origin [paste the link you copied]
$ git push origin master
```
- *What's going on??*
  - The link you copied is the link to your remote repository
  - `origin` is the name of the name of your remote. You don't always have to name is `origin` but it is the convention
  - The second line pushes the changes you made locally on to your remote repository using (you guessed it), the remote `origin`
  - `master` is the name of branch you will be pushing to
  - Think of it as your base or starting point
