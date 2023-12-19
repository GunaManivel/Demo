# Demo

## This is a repository used to learn about Git and GitHub

*steps to be followed to create this* 

+ create an empty repository named `demo` in [GitHub](https://github.com/new)

+ copied contents from the page titled  `create a new repository on the command line`

```
echo "# new" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GunaManivel/new.git
git push -u origin main
```
+ created an empty folder in my file explorer and open the folder in cmd  then just copy paste the commands and execute the lines one by one.

+ First command creates an empty repository `init`
+  `git add README.md` adds the file to the staging area
+ `git commit -m "commit message"` commit the file to the local git
+ `git branch -M main` used to identify the branch of the repository
+  `git remote add origin https://github.com/GunaManivel/new.git` used to identify the repository to add the files
+ `git push -u origin main` used to push th files in GitHub

