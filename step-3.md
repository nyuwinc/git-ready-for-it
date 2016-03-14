# Step 3

### Create a new branch
```
$ git checkout -b [ branch name ]
```
- This creates a new branch and switches to it
- Now run the following on your command line
```
$ git branch
```
- And you should have something like this
```
master
* [ branch name ]
```
- The `*` indicates the branch you are on

### Make a change to your README.md
- Add anything, remove anything, do anything to your file
- We highly suggest using [Open Ipsum](https://openipsum.com/) for fun text

### Checkout and commit
- Add, commit, and push your changes to your current branch
- This time, we will just be adding the `.md` file. You **will not** be using `add .`
- Remember, you **won't be** be pushing to master. You'll be pushing to the branch you create
- Here are the commands
```
$ git add README.md
$ git commit -m "[ Your message ]"
$ git push origin [ branch name ]
```
