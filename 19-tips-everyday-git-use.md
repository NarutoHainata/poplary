# 19 Tips For Everyday Git Use
http://www.alexkras.com/19-git-tips-for-everyday-use/

1. Parameters for better logging: `git log --online --graph`
2. Log actual changes in a file: `git log -p filename`
3. Only log changes for some specific lines in file: `git log -L 1,1:filename`
4. Log changes not yet merged to the parent branch: `git log --no-merges master..branch`
5. Extract a file from another branch: `git show some-branch:filename > outputfile`
6. Some notes on rebasing: `git pull --rebase`
7. Remember the branch structure after a local merge: `git merge --no-ff`
8. Fix your previous commit, instead of making a new commit: `git commit --amend`
9. Three stages in git, and how to move between them:
    * `git reset --hard HEAD`
    * `git status -s`
10. Revert a commit, softly: `git revert -n`
11. See diff-erence for the entire project (not just one file at a time) in a 3rd party diff tool: `git difftool -d`
12. Ignore the white space: `git diff -w`
13. Only "add" some changes from a file: `git add -p`
14. Discover and zap those old branches: `git branch -a`
15. Stash only some files: `git stash -p`
16. Commit Message
17. Auto Completion
18. Aliases
19. Find out the broken commit: `git bisect`