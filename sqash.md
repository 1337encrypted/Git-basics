# Squash

- If you wish to merge some of your commits into a single commit then you can squash your commits into a single commit

```
git rebase -i HEAD~<number>
```

here <number> is how many commits you want to squash

## Example:   

```
git rebase -i HEAD~3
```

This will squash the last 3 commits.

