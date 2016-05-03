#Installation

**TODO: installation script**

* Copy this repository with 
```
git clone git@github.com:neustroev/git-compare.git
```

* a. Copy `git-compare` file to a folder from your `$PATH`.
  b. Add repository folder to your path by adding
```
  PATH=$PATH:path/to/git-compare
```
to your `~/.bashrc`, `~/.zshrc`, etc.

* Restart your terminal.

#Usage
When in a git repository folder, in your terminal:

* `git compare` - to view diff for current remote branch with default base.
* `git compare <base>` - to view diff for current remote branch with selected base.
* `git compare <base> <branch>` - to view for selected branch with selected base.
