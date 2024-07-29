# Submodule
### Note: you need to commit and push the submodule first before commiting and pushing the parent module

# How to Add a Git Submodule

A Git submodule allows you to include and manage repositories within your main repository.

## Step 1: Navigate to Your Main Repository

Open your terminal and navigate to the root directory of your main repository where you want to add the submodule.

```
cd /path/to/your/main/repository
```
## Step 2: Create and Switch to a New Branch (Optional)   
If you want to add the submodule on a new branch, create and switch to the new branch.  

```
git checkout -b new-branch-name
```
## Step 3: Add the Submodule
Add the submodule using the git submodule add command.  
Replace <submodule-repository-url> with the URL of the submodule repository, and <path/to/submodule> with the path where you want to place the submodule in your repository.   

```
git submodule add <submodule-repository-url> <path/to/submodule>
```

## Step 4: Initialize and Update the Submodule   
Initialize and fetch the data for the submodule.   
```
git submodule update --init --recursive
```

## Step 5: Commit the Changes  
Commit the changes to your repository. This includes the updated .gitmodules file and the submodule directory.  
```
git add .gitmodules <path/to/submodule>
git commit -m "Added submodule <submodule-name>"
```

## Step 6: Push the Changes
Push the changes to the remote repository.  
```
git push origin new-branch-name
```

