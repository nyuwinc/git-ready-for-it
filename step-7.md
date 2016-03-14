# Step 7

### Local Branch
- On **your** repo, create a branch with the same name as the branch your partner just created on your repo
- For example, if your partner pushed to a branch called `brown-branch`, your command should look like this
```
$ git checkout -b brown-branch
```
- Now, checkout to your master branch and merge the changes on your partner's branch
```
$ git checkout master
$ git merge [ partner branch ]
```
- You should run into a merge conflict

### MERGE CONFLICT!!!
- Don't panic, it's only a merge conflict!
- It should tell you where your merge conflict is (it should be in the `README.md` file)
- Open up the `README.md`
- You should see something that looks like this
```
<<<<<<<<< HEAD
Your cool text is here
=========
Your partner's cool text is here
>>>>>>>>> [ your partner's branch name ]
```

### What is going on??
- `<<<<<<<<<<< HEAD` indicates where your current HEAD is pointing to
- `>>>>>>>>>>> [ partner's branch ]` indicates where your partner's branch is pointing to
- `==========` Tells you were your HEAD ends and where your partner's head starts

### Now what??
- Remove or keep text as you please
- Remove `<<<<<<<<<<< HEAD`, `>>>>>>>>>>>` and `==========`
- Add, commit, push
