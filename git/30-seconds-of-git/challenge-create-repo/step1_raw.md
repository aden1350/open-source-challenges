---
title: Create a new repository
---

Initializes a new git repository, setting up all the configuration files needed by git.

- Use `git init` to initialize an empty repository in the current directory.
- Alternatively, use `git init [<directory>]` to initialize the repository in the specified `<directory>`.
- Note: Running `git init` in an existing repository is safe.
- Note: You only need to run `git init` once per repository.

```shell
git init [ < directory > ]
```

```shell
cd ~/my_project
git init # Initializes a repo in ~/my_project

cd ~
git init my_project # Initializes a repo in ~/my_project
```
