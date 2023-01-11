# creating new github branch and working with it from your terminal:

- create new branch and switch to it immediately:

```
~ git switch -c [name of branch]
```

- push new branch to remote git repository:

```
~ git push -u origin [name of branch]
```

- check which branches you have locally:

```
~ git branch
```

- switch to specific branch:

```
~ git switch [name of the branch]
```

- switch between branches back and forth:

```
~
```

- commit session notes changes to new branche:

```
~ git add .
~ git commit -m "commit message"
~ git push
```

- check your commit status:

```
~ git status
```

if you get the message "nothing to commit, working tree clean", everything is up to date.

- create a pull request to the main branch:

```
~ git pull
```

Go to your github page and select the branch you are working on. On the top right side should now be a green button "Compare & pull request". Click on it. There you can add a message and reviewers to check your request. The reviewer/s can then comment on your file, approve it or immedetely commit (merge) it to main (this is not usual, the commit should be done by you after the file is reviewed).

Let's say the reviewer approved your request. Now you can commit it and merge with the main branch by clicking on "Merge pull request" on your github page. Then click "confirm merge".

Now you should get the message **"pull request successfully merged and closed"**. Beside the message, it shows you now a button **"delete branch"**. As all the commits you did on that branch are already commited and merged with the **main** branch, it is safe to delete it. The commit history is now merged in the **main** branch and you will still have access to it there.
