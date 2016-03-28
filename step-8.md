# Step 8

In Step 6 and Step 7, you learned about merging and merge conflicts. This step shows you how to merge without the conflicts

### On ***your*** repo
- Navigate to **your** local repo
- Open up your README file and make a change
- Add, commit, and push

### On ***your partner's*** repo
- Navigate to **your partner's** local repo on your computer
- Pull from `origin master`
```
git pull origin master -f
```
- Open up your partner's README file and edit it
- Add, commit, and push to master

### Back to ***your*** repo
- Pull from `origin master`

### **How is this happening??**
In Step 6 and Step 7, you and your partner were both altering the same file. In this step, Step 8, you pushed your local changes to the repo before your partner made an edit. The file your partner altered was the file you just pushed. Git recognized the two files were at different states and automatically merged the files
### **How is this relevant??**
IRL, you're going to be working with other people on projects and repos. You should get used to pushing, merging, and fixing merge conflicts because you'll encounter them often. Keep practicing merging and solving merge conflicts!

