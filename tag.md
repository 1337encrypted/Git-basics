# Git supports two types of tags: lightweight and annotated.
- A lightweight tag is very much like a branch that doesn’t change — it’s just a pointer to a specific commit.
- Annotated tags, however, are stored as full objects in the Git database

## Annotated Tags
- git tag -a v1.4 -m "my version 1.4"

## Lightweight Tags
- git tag v1.4-lw

## Show all tags
- git tag

## Show a specific tag
- git show v1.4-lw

## Tag a specific commit
- git tag -a v1.2 9fceb02

## Share all tags
- git push origin --tags

## Sharing a tag
- git push origin v1.5

# Deleting Tags
- git tag -d v1.4-lw

## After deleting the tag push it to remote
- git push origin :refs/tags/v1.4-lw
- git push origin --delete <tagname>

# Checkout to a tag
git checkout v2.0.0
