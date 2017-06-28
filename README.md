# utils

Miscellaneous utilities and scripts

*   `darcs-to-git` - a script for synchronization of darcs repository with git
    repository, darcs repository can be read/write (provided the history
    exported to git is not reorganized), the git mirror has to be read only; it
    uses a shadow branch in the git repo to keep synchronization marks.
