# Step 7

### On **your** repo
- Pull from master like so
```
git pull origin master -f
```

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
- Keep practicing creating and resolving merge conflicts
