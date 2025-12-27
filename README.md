# Follow below git code to make changes
```sh
git fetch --all

git checkout -b <branch-name> origin/main
```
Then make changes or write code

```sh
git status
git add --patch (do not add .ipynb_checkpoints)

git commit -m "update msg"

git push origin <branch-name>
```
