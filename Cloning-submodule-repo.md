# Cloning the Repository with Submodules  
To clone a repository that includes submodules, use the --recursive flag to ensure that all submodules are cloned as well.  
```
git clone --recursive <repository-url>
```   
If you have already cloned the repository without the --recursive flag, initialize and update the submodules with:   
```
cd /path/to/cloned/repository
git submodule update --init --recursive
```
