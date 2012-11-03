Useful Utilities
================

NOTE
----
After adding a new directory it will need to be added to your `PATH` to make it nice and easy.

- export PATH="$HOME/opt/git/bin:$PATH"

Git Shorthand
-------------
The git helpers are mostly shorthand for common day to day tasks;

- addall: `git add .`
- amend: `git commit --amend`
- gitlog: `git log --pretty=format:"%h - %an, %ar: %s" --graph`
- pull: `git pull --rebase`
- push: `git push`

Most are very basic, and some just reinforce a working methodology that I like to stick to, like re-baseing on *pull*s. You can also really speed things up by linking shorthands; `addall;amend` or `pull;push`.
