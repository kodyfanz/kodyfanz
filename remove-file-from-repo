# Remove existing .DS_Store files from the repository:
```sh
find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch
```
Add this line:
```sh
.DS_Store
```
to the file `.gitignore`, which can be found at the top level of your repository (or create the file if it isn't there already). You can do this easily with this command in the top directory:
```sh
echo .DS_Store >> .gitignore
```
Then commit the file to the repo:
```sh
git add .gitignore
git commit -m '.DS_Store banished!'
```
