# git-wip

"Git Work-In-Progress"

`git-wip` will grab the uncomitted changes in your current working directory
and push them to a new branch on origin called `<yourbranch>.WIP`. Untracked
files also come along for the ride - in fact even the contents of your staging
area is recorded.

`git-unwip` can then be used on a clean local checkout of `<yourbranch>` - it
will pull the remote `<yourbranch>.WIP` branch from origin and restore your
uncommitted changes, untracked files and index.
