# bash-favdir
Added shortcut directories and swiftly switch to them.

# Command examples
```
# You may add this line to your ~/.profile or ~/.bashrc
% source /path/to/bash-favdir

# Add $PWD to favorites
% fadd

# List the current favorited directories
% flist									

# List the current favorited directories whose name contains "github"
% flist github

# Change dir to th directory whose name contains "github", if multiple dirs match then you may be prompted all and choose one
% fcd github

# fpushd is the same as fcd except that s/cd/pushd/
% fpushd 

# Delete a patther
% fdel github

```



