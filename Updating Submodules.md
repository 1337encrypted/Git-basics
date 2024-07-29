# Updating Submodules
## Navigate to the submodule directory:
```
cd <path/to/submodule>
```
## Pull the latest changes:
```
git pull origin $(git rev-parse --abbrev-ref HEAD)
```
## Return to the main repository and commit the updated submodule reference:
```
cd ..
git add <path/to/submodule>
git commit -m "Updated submodule to latest commit"
git push
```
