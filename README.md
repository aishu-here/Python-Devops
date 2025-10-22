# This is the README file, help to push the code

1. Initialize teh git folder
```
git init
```

to cross verify, checkout the root or the folder where you have initalized the git by
```
ls -a
```

2. Add all the untracked files for staging

```
git add .
```

or add the single file 
```
git add <filename>
```

3. Commit all your changes
```
git commit -m "message here..."
```

4. If you are doing it for the first time, then set the branch to main 
```
git branch -m Main 
```

5.Set the remote origin by
```
git remote add origin <repo url here...>
```

6. push all your changes
```
git push origin main
```

Note: If you've already pushed once then set the upstream to main 
```
git push --set-upstream origin main
```

After this on every subsequent push you can just simply do the set 2 and 3 after than just push the code by `git push`