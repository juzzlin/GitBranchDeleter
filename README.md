# Git Branch Deleter
Small PyGTK-based utility program to delete Git branches

## What the hell is this?

This is for people who use Git via the terminal (on Linux) and find it annoying to delete branches when there are a lot of them.

Usage (within your repository):

```
$ ./git-branch-deleter
```
Delete with `-D`:
```
$ ./git-branch-deleter -D
```

Check the branches you want to delete and click `Apply`.

## Limitations

Currently deletes **local** branches only.

## Dependencies and assumptions

* Python 3
* PyGTK 3
* `git` executable must be in `PATH`

## License

MIT
