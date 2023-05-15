# Gym-Git-Exercise-Solution
git exercise
# git exercise

## bundle 1

### ex1
***bash
1@DESKTOP-QOH1F4K MINGW64 ~/Desktop
$ git config --global user.email "findekwe@gmail.com"

1@DESKTOP-QOH1F4K MINGW64 ~/Desktop
$ git config --global init.default branch main

1@DESKTOP-QOH1F4K MINGW64 ~/Desktop
$ cd d:/gitex

1@DESKTOP-QOH1F4K MINGW64 /d/gitex
$ git init
Initialized empty Git repository in D:/gitex/.git/

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (master)
$ git mv "master" "main"
fatal: bad source, source=master, destination=main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        perfect.html

nothing added to commit but untracked files present (use "git add" to track)

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (master)
$ git branch "master" "main"
fatal: not a valid object name: 'main'

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (master)
$ git branch -m master main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git add perfect.html

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   perfect.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   perfect.html


1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git -a -m "changes in perfect.html"
unknown option: -a
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git add perfect.html

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   perfect.html


1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git commit -m "perfect.html gitexercise"
[main (root-commit) 4b53bab] perfect.html gitexercise
 1 file changed, 71 insertions(+)
 create mode 100644 perfect.html

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git  remote add orgin https: //github.com/indekwe/Gym-Git-Exercise-Solution
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch -M mai

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (mai)
$ git branch -M main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push -u orgin main
fatal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push -u origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git remote add origin ^C

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git remote add origin https: //github.com/indekwe/Gym-Git-Exercise-Solution
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git remote add origin main https: //github.com/indekwe/Gym-Git-Exercise-Solution
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git status
On branch main
nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch -M main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push -u origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ ^C

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git remote add origin main https: //github.com/indekwe/Gym-Git-Exercise-Solution
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch -M main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push -u origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git remote add origin main https://github.com/indekwe/Gym-Git-Exercise-Solution.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch -M main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push -u origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git remote add origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch -M main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push -u origin main
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push --help

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git fetch origin main:tmp
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 617 bytes | 5.00 KiB/s, done.
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * [new branch]      main       -> tmp
 * [new branch]      main       -> origin/main

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git remote -v
origin  https://github.com/indekwe/Gym-Git-Exercise-Solution.git (fetch)
origin  https://github.com/indekwe/Gym-Git-Exercise-Solution.git (push)

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch
* main
  tmp

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git rebase tmp
Successfully rebased and updated refs/heads/main.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.30 KiB | 189.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   5ae1cf2..973b921  main -> main
branch 'main' set up to track 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch dev

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git branch
  dev
* main
  tmp

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (main)
$ git switch dev
Switched to branch 'dev'

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (dev)
$ git branch test

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (dev)
$ git switch test
Switched to branch 'test'

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (test)
$ git branch -d
fatal: branch name required

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (test)
$ git switch dev
Switched to branch 'dev'

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (dev)
$ git branch -d test
Deleted branch test (was 973b921).

1@DESKTOP-QOH1F4K MINGW64 /d/gitex (dev)
$

***
