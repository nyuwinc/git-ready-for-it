# Step 4

### Checkout to the master
- The changes you made on your branch will now be merged to your master branch
- But first, we need to checkout back to the master branch
```
$ git checkout master
```

### Merge!
- Run the following on your command line
```
$ git merge [ branch name ]
```
- This will combine the changes you made on your branch to the master branch
- If you run into something which says `CONFLICT` or `merge conflict` raise your hand!

### Delete the branch you made your changes on
- You don't need it anymore
```
$ git branch -d [ branch name ]
```
