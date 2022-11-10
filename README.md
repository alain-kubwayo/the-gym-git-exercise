# GIT Exercises

This project is created to contain all solutions to the series of GIT exercises provided by The Gym Rwanda.

## Bundle 1

### Exercise 1

```bash
➜  git mkdir the-gym-git-exercises
➜  git ls
the-gym-git-exercises
➜  git cd the-gym-git-exercises 
➜  the-gym-git-exercises git init
Initialized empty Git repository in /Users/alain/Documents/the-gym/git/the-gym-git-exercises/.git/
➜  the-gym-git-exercises git:(main) code .
➜  the-gym-git-exercises git:(main) git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
➜  the-gym-git-exercises git:(main) ✗ git add README.md
➜  the-gym-git-exercises git:(main) ✗ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

➜  the-gym-git-exercises git:(main) ✗ git commit -m "initialize project"
[main (root-commit) df498e9] initialize project
 1 file changed, 3 insertions(+)
 create mode 100644 README.md
➜  the-gym-git-exercises git:(main) git remote add origin https://github.com/alain-kubwayo/the-gym-git-exercise-solutions.git
➜  the-gym-git-exercises git:(main) git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 320 bytes | 320.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alain-kubwayo/the-gym-git-exercise-solutions.git
 * [new branch]      main -> main
➜  the-gym-git-exercises git:(main) git checkout -b dev
Switched to a new branch 'dev'
➜  the-gym-git-exercises git:(dev) git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/alain-kubwayo/the-gym-git-exercise-solutions/pull/new/dev
remote: 
To https://github.com/alain-kubwayo/the-gym-git-exercise-solutions.git
 * [new branch]      dev -> dev
➜  the-gym-git-exercises git:(dev) git checkout -b test
Switched to a new branch 'test'
➜  the-gym-git-exercises git:(test) git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/alain-kubwayo/the-gym-git-exercise-solutions/pull/new/test
remote: 
To https://github.com/alain-kubwayo/the-gym-git-exercise-solutions.git
 * [new branch]      test -> test
➜  the-gym-git-exercises git:(test) git checkout dev
Switched to branch 'dev'
➜  the-gym-git-exercises git:(dev) git branch -D test
Deleted branch test (was df498e9).
➜  the-gym-git-exercises git:(dev) git push origin --delete test
To https://github.com/alain-kubwayo/the-gym-git-exercise-solutions.git
 - [deleted]         test
➜  the-gym-git-exercises git:(dev) 
```