# Installation

**TODO: installation script**

## Step 1
Copy this repository with 
```
git clone git@github.com:neustroev/git-compare.git
```

## Step 2
Copy `git-compare` file to a folder from your `$PATH`

**OR**

Add repository folder to your path by adding this to your `~/.bashrc`, `~/.zshrc`, etc:
```
PATH=$PATH:path/to/git-compare
```

## Step 3
Restart your terminal.

# Usage
When in a git repository folder, in your terminal:

* `git compare` - to view diff for current remote branch with default base.
* `git compare <base>` - to view diff for current remote branch with selected base.
* `git compare <base> <branch>` - to view for selected branch with selected base.
