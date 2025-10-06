# Datasets

Here lie the datasets for the [Desbordante](https://github.com/Mstrutov/Desbordante) platform.

You can check the contents in the corresponding `.txt` files -- they are automatically generated from the zip-archives via git-hooks. 

## Hooks

To keep dataset lists up-to-date, it is recommended to set up the pre-commit hook, which will
automatically update dataset lists:
```bash
chmod +x .githooks/pre-commit && ln -sv ../../.githooks/pre-commit .git/hooks/pre-commit
```

Due to git limitations, generated `.txt` files won't be listed in commit message editor, but they will be tracked.
