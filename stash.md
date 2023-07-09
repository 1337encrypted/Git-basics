Stash is basically to save your current non committed progress and maybe come back later and work upon it.
Ideally if you want to checkout to another branch without saving current progress you would consider stashing.

| Description | command |
| :--- | :--- |
| To stash progress |`git stash save 'reason for stashing'`|
| To list all stashes|`git stash list`|
| To get back stashed items| `git stash apply <stash@(number)>` |


