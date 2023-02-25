# git stash --staged 

git stash's new --staged mode makes it easy to stash away what you already have in the staging area, and nothing else. You can think of it like git commit (which only writes staged changes), but instead of creating a new commit, it writes a new entry to the stash. Then, when you’re ready, you can recover your changes (with git stash pop) and keep working.