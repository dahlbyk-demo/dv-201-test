<h1>DeltaV Git Good Guide</h1>

<h2>Set Up Local Project</h2>

<h3>Initialize New Project</h3>

```
git init
```

<h3>From GitHub</h3>

```
git clone https://github.com/my-user/my-project.git
```

<h2>ACP: Add, Commit, Push</h2>

<h3>Add New File or Changes</h3>

Used to tell Git that current changes should be saved in the next commit.

To add ("stage") all changes:

```
git add .
```

Or you can stage/add individual files:

```
git add <filename>
```

<h3>Save Change in Git</h3>

To save the added changes into history, commit with a useful, descriptive message.

```
git commit -m "This is my message"
```

<del>
**Note:** You can also leave off `-m` to open an editor to type your commit message.
</del>

To use an editor other than Vim, set `core.editor`:

```
git config --global core.editor "atom --wait"
```

<h4>Review Changes Before Committing</h4>

To view changes that have not been added:

```
git diff
```

To review changes that have been added:

```
git diff --staged
```
