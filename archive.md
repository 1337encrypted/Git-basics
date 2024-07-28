# Git archive

- Git archive is used to zip your project into a tarball, it does not contain the .git directory so its a way of packing a commit as a zip file.

## Syntaix: The hard way   

```
git archive --format-tar --prefix=<folder_name/> HEAD | gzip > <folder_name.tar.gz>
```

## Syntax: The better way

```
git archive --prefix=<folder_name/> -o <folder_name.tar.gz>
```

