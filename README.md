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
### ex 2
  1@DESKTOP-QOH1F4K MINGW64 ~/Desktop
$ cd d;/STASH
bash: cd: d: No such file or directory
bash: /STASH: No such file or directory

1@DESKTOP-QOH1F4K MINGW64 ~/Desktop
$ cd d:/STASH

1@DESKTOP-QOH1F4K MINGW64 /d/STASH
$ git config --global user.name "indekwe"

1@DESKTOP-QOH1F4K MINGW64 /d/STASH
$ git config --global user.email "findekwe@gmail.com"

1@DESKTOP-QOH1F4K MINGW64 /d/STASH
$ git config --global init.default branch main

1@DESKTOP-QOH1F4K MINGW64 /d/STASH
$ git init
Initialized empty Git repository in D:/STASH/.git/

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Home.html
        stash.html

nothing added to commit but untracked files present (use "git add" to track)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Home.html
        stash.html

nothing added to commit but untracked files present (use "git add" to track)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git add Home.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Home.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Home.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Home.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash save
You do not have the initial commit yet

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git commit -m "this will be stashed"
[master (root-commit) 6c48ddc] this will be stashed
 1 file changed, 78 insertions(+)
 create mode 100644 Home.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Home.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash save
Saved working directory and index state WIP on master: 6c48ddc this will be stashed

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash list
stash@{0}: WIP on master: 6c48ddc this will be stashed

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        About.html
        stash.html

nothing added to commit but untracked files present (use "git add" to track)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git add About.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   About.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   About.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git commit -m "need stash about"
[master 11ed3e5] need stash about
 1 file changed, 82 insertions(+)
 create mode 100644 About.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   About.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash save
Saved working directory and index state WIP on master: 11ed3e5 need stash about

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash list
stash@{0}: WIP on master: 11ed3e5 need stash about
stash@{1}: WIP on master: 6c48ddc this will be stashed

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html
        team.html

nothing added to commit but untracked files present (use "git add" to track)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git add team.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git log --oneline
11ed3e5 (HEAD -> master) need stash about
6c48ddc this will be stashed

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git commit -m "need team stash to survive"
[master 07e948c] need team stash to survive
 1 file changed, 87 insertions(+)
 create mode 100644 team.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash save
Saved working directory and index state WIP on master: 07e948c need team stash to survive

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash list
stash@{0}: WIP on master: 07e948c need team stash to survive
stash@{1}: WIP on master: 11ed3e5 need stash about
stash@{2}: WIP on master: 6c48ddc this will be stashed

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git stash pop stash@{2}
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Home.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{2} (7b8ec909318abd4ee395515872b7380b10348c91)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git add Home.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git commit -m "home stash commited"
[master fdeaa6b] home stash commited
 1 file changed, 1 insertion(+)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git remote add origin https;//github.com/indekwe/Gym-Git-Exercise-Solution
bash: //github.com/indekwe/Gym-Git-Exercise-Solution: No such file or directory

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git bramch -m master
git: 'bramch' is not a git command. See 'git --help'.

The most similar command is
        branch

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git branch -M master

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git push -u origin master
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git remote add origin https://github.com/indekwe/Gym-Git-Exercise-Solution
error: remote origin already exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git push -u origin master
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https'

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git branch
* master

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git branch -N "master" "main"
error: unknown switch `N'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (master)
$ git branch -m "master" "main"

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git remote add origin https://github.com/indekwe/Gym-Git-Exercise-Solution
error: remote origin already exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git rebase
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-rebase(1) for details.

    git rebase '<branch>'

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> main


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git rebase main
Current branch main is up to date.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git remote add origin https://github.com/indekwe/Gym-Git-Exercise-Solution
error: remote origin already exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git branch
* main

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push --all
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git remote -v
origin  https (fetch)
origin  https (push)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git remote add origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: remote origin already exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/1/.ssh/id_rsa):
Created directory '/c/Users/1/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/1/.ssh/id_rsa
Your public key has been saved in /c/Users/1/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:6ojISh5aTaLTFc8pXxz0VTE4sH3MTr8aeior/0qSyxo 1@DESKTOP-QOH1F4K
The key's randomart image is:
+---[RSA 3072]----+
|        . ...o+. |
|       . . +oo . |
|    .   . o ..=  |
|     + o .   + . |
|  . + + S     . .|
| o = o o.       .|
|ooo .Eoo .   . . |
|=+.. oo.+.  ..o  |
|=o. ..ooo+=+o.   |
+----[SHA256]-----+

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ ^C

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ cat /c/Users/1/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC4qUDOv0vgiSQhF9GHGFXw/96KCTAfcrPUW+KSsoJCc2jNfag62adF+0MTQnqLFdDtrimAc13+rA3NA46VLOwE882TVol+H4vxQ3KBRlJaZyoveE9t1839JGo6FuKYPhKt5xTLAJFCbCr9riZa36eH4FzlWJBsdsZxhuv2F9HbAbFoUCqxHXmBJLeGYw26FexhnIdxosrtvPafX8OhwQNrqIubS/SDLax+Xf2LP1R8dtPq03PBU6BWPid+6ws6Xrow7hcBQZRFsGFEHh/DSvYhqHuUEIXLEPw3+f6A9qXn1jzUTdFzoI+b+yRNkTRtII8xIO0zoGMbs5NHEjzEQxg8HhSzU8utJHkVC+cxOB4lbI6umUVR+81tymQdYHbCozSecGuS1E/zCuRu9/yBL6CfGPxr4rW5PDHyJPNImqsiANyezYUm3YUAO4A/LD6Ho/tew1vO5u7LKHiFarcbGqX7ffvbDb7By8NGjR8YdQjALckUd34efMZBjqWpiU2G4mk= 1@DESKTOP-QOH1F4K

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push --all
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git remote add origin git@github.com:indekwe/Gym-Git-Exercise-Solution.git
error: remote origin already exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push origin -u main
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ cd .ssh
bash: cd: .ssh: No such file or directory

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git fetch
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https'

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
fatal: 'https' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ ^C

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git remote set origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: unknown subcommand: `set'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git remote set-url origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git rebase
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-rebase(1) for details.

    git rebase '<branch>'

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> main


1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git rebase main
Current branch main is up to date.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git pull rebase
fatal: 'rebase' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git pull rebase^C

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git fetch main
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git fetch origin main
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 9 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (9/9), 4.37 KiB | 13.00 KiB/s, done.
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git rebase main
Current branch main is up to date.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git pull --rebase origin main
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/main.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git log
commit 388164dfc3a709cc26ddd30e310b602f5e611e00 (HEAD -> main)
Author: indekwe <findekwe@gmail.com>
Date:   Wed May 17 17:50:03 2023 -0700

    home stash commited

commit 78d1915a62a015dfd02436140c57e84f616ca9ad
Author: indekwe <findekwe@gmail.com>
Date:   Wed May 17 17:45:58 2023 -0700

    need team stash to survive

commit 83a733f91b433488ef5ef5cc89e81da0de7e0250
Author: indekwe <findekwe@gmail.com>
Date:   Wed May 17 17:33:31 2023 -0700

    need stash about

commit 7653786f8de131d722c3fadb7e4e2f13bcdfb01c
Author: indekwe <findekwe@gmail.com>
Date:   Wed May 17 17:22:03 2023 -0700

    this will be stashed

commit 9a47dad106abee58a2c166f5cd46d69a6c3873e1 (origin/main)
Author: indekwe <131709694+indekwe@users.noreply.github.com>
Date:   Mon May 15 09:49:11 2023 -0700

    Update README.md

commit 973b9215af76f1218beb6ce29b8717cad4f72688
Author: indekwe <findekwe@gmail.com>
Date:   Mon May 15 08:10:13 2023 -0700

    perfect.html gitexercise

commit 5ae1cf2e2243309cbb1da1380970740900cd793c
Author: indekwe <131709694+indekwe@users.noreply.github.com>
Date:   Mon May 15 05:26:23 2023 -0700

    Initial commit

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 1.53 KiB | 784.00 KiB/s, done.
Total 12 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), done.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   9a47dad..388164d  main -> main
branch 'main' set up to track 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git stash list
stash@{0}: WIP on master: 07e948c need team stash to survive
stash@{1}: WIP on master: 11ed3e5 need stash about

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   About.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{1} (cd11ceccb10d2e3d61712bef6845d4ab37c3213f)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git add About.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git commit -m "About stash commited"
[main e584c69] About stash commited
 1 file changed, 1 insertion(+)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 372 bytes | 372.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   388164d..e584c69  main -> main
branch 'main' set up to track 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git stash list
stash@{0}: WIP on master: 07e948c need team stash to survive

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git stash pop stash@{0}
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{0} (ea56b81820bc3d2ce6855e89e5290b09cb931a10)

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git reset
Unstaged changes after reset:
M       team.html

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        stash.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$ git diff
diff --git a/team.html b/team.html
index bb4a6f8..2b3b38e 100644
--- a/team.html
+++ b/team.html
@@ -14,6 +14,7 @@
                 <div>
                     <h1 class="font-bold uppercase p-20">
                         <a href="/">Food</a>
+                        <p>Food for you teams , are here</p>
                     </h1>
                 </div>
                 <ul>

1@DESKTOP-QOH1F4K MINGW64 /d/STASH (main)
$
USER L@NIYO-T MINGW64 ~/vscode (master)
$ git config --global user.name "indekwe"

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git config --global user.email "findekwe@gmail.com"

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git config --global init.default branch master

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git init 
Reinitialized existing Git repository in C:/Users/USER L/vscode/.git/

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/test.css
        deleted:    test.html/test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        animation.html
        codewars/
        cssgridgame.css
        cssgridgame.html
        flex.html
        test.html/justify-align.html
        test.html/out.css
        test.html/out.html
        test.html/services.html
        w3.html

no changes added to commit (use "git add" and/or "git commit -a")

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git --add test.html/service.html
unknown option: --add
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git add test.html/service.html
fatal: pathspec 'test.html/service.html' did not match any files

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)        
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/test.css
        deleted:    test.html/test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        animation.html
        codewars/
        cssgridgame.css
        cssgridgame.html
        flex.html
        test.html/justify-align.html
        test.html/out.css
        test.html/out.html
        test.html/services.html
        w3.html

no changes added to commit (use "git add" and/or "git commit -a")

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git add test.html/services.html

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test.html/services.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html
        modified:   test.html/test.css
        deleted:    test.html/test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        animation.html
        codewars/
        cssgridgame.css
        cssgridgame.html
        flex.html
        test.html/justify-align.html
        test.html/out.css
        test.html/out.html
        w3.html


USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git commit -m "services commited"
[ft/bundle-2 1fc0acd] services commited    
 1 file changed, 83 insertions(+)
 create mode 100644 test.html/services.html

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git remote add origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: remote origin already exists.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git remote set origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: unknown subcommand: `set'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git branch -M main

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git branch
* main
  master

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git branch -M ft/bundle-2

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push -u origin
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push --set upstream origin ft/bundle-2
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin ft/bundle-2
error: cannot pull with rebase: You have unstaged changes.
error: please commit or stash them.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html
        modified:   test.html/test.css
        deleted:    test.html/test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        animation.html
        codewars/
        cssgridgame.css
        cssgridgame.html
        flex.html
        test.html/justify-align.html
        test.html/out.css
        test.html/out.html
        w3.html

no changes added to commit (use "git add" and/or "git commit -a")

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git commit -m "services commited"
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html
        modified:   test.html/test.css
        deleted:    test.html/test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        animation.html
        codewars/
        cssgridgame.css
        cssgridgame.html
        flex.html
        test.html/justify-align.html
        test.html/out.css
        test.html/out.html
        w3.html

no changes added to commit (use "git add" and/or "git commit -a")

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html
        modified:   test.html/test.css
        deleted:    test.html/test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        animation.html
        codewars/
        cssgridgame.css
        cssgridgame.html
        flex.html
        test.html/justify-align.html
        test.html/out.css
        test.html/out.html
        w3.html

no changes added to commit (use "git add" and/or "git commit -a")

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git log oneline
fatal: ambiguous argument 'oneline': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git log --oneline
1fc0acd (HEAD -> ft/bundle-2) services commited
996cec0 (origin/master, master) implement grid layout

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin ft/bundle-2
error: cannot pull with rebase: You have unstaged changes.
error: please commit or stash them.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git stash
Saved working directory and index state WIP on ft/bundle-2: 1fc0acd services commited

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin ft/bundle-2
fatal: couldn't find remote ref ft/bundle-2

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git diff

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git log
commit 1fc0acd3cfbdb538ae63a978f4737ca933c17216 (HEAD -> ft/bundle-2)
Author: indekwe <findekwe@gmail.com>
Date:   Sat May 20 15:27:09 2023 +0200

    services commited

commit 996cec0ea0a72bff3efdc04f4e788bab298f2a9a (origin/master, master)
Author: indekwe <findekwe@gmail.com>
Date:   Sun May 7 16:26:52 2023 +0200

    implement grid layout

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push u- origin ft/bundle-2
error: src refspec origin does not match any
error: failed to push some refs to 'u-'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git fetch

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push --set upstream origin ft/bundle-2
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push --rebase origin ft/bundle-2
error: unknown option `rebase'
usage: git push [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --repo <repository>   repository
    --all                 push all refs
    --mirror              mirror all refs
    -d, --delete          delete refs
    --tags                push tags (can't be used with --all or --mirror)
    -n, --dry-run         dry run
    --porcelain           machine-readable output
    -f, --force           force updates
    --force-with-lease[=<refname>:<expect>]
                          require old value of ref to be at this value
    --force-if-includes   require remote updates to be integrated locally
    --recurse-submodules (check|on-demand|no)
                          control recursive pushing of submodules
    --thin                use thin pack
    --receive-pack <receive-pack>
                          receive pack program
    --exec <receive-pack>
                          receive pack program
    -u, --set-upstream    set upstream for git pull/status
    --progress            force progress reporting
    --prune               prune locally removed refs
    --no-verify           bypass pre-push hook
    --follow-tags         push missing but relevant tags
    --signed[=(yes|no|if-asked)]
                          GPG sign the push
    --atomic              request atomic transaction on remote side
    -o, --push-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only


USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin ft/bundle-2
fatal: couldn't find remote ref ft/bundle-2

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin main
fatal: couldn't find remote ref main

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git branch
* ft/bundle-2
  master

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin master
From https://github.com/indekwe/css-grid
 * branch            master     -> FETCH_HEAD
Current branch ft/bundle-2 is up to date.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push --set upstream origin ft/bundle-2
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push u- origin ft/bundle-2
error: src refspec origin does not match any
error: failed to push some refs to 'u-'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push u- origin master
error: src refspec origin does not match any
error: failed to push some refs to 'u-'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push --set upstream origin master
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git switch master
Switched to branch 'master'

USER L@NIYO-T MINGW64 ~/vscode (master)
$ git branch -N main
error: unknown switch `N'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


USER L@NIYO-T MINGW64 ~/vscode (master)
$ git branch -M main

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git push --set upstream origin main
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git push --set upstream origin main
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git remote set origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: unknown subcommand: `set'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


USER L@NIYO-T MINGW64 ~/vscode (main)
$ git remote add origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: remote origin already exists.

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git remote set origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: unknown subcommand: `set'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


USER L@NIYO-T MINGW64 ~/vscode (main)
$ git remote set-url origin https://github.com/indekwe/Gym-Git-Exercise-Solution.gitA

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git switch
fatal: missing branch or commit argument

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git branch
  ft/bundle-2
* main

USER L@NIYO-T MINGW64 ~/vscode (main)
$ git switch ft/bundle-2
Switched to branch 'ft/bundle-2'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git remote set-url origin https://github.com/indekwe/Gym-Git-Exercise-Solution.gitA

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push --set upstream origin ft/bundle-2
error: src refspec origin does not match any
error: failed to push some refs to 'upstream'

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push -u origin main
remote: Repository not found.
fatal: repository 'https://github.com/indekwe/Gym-Git-Exercise-Solution.gitA/' not found

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git remote set-url origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push -u origin main
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin ft/bundle-2
fatal: couldn't find remote ref ft/bundle-2

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git pull --rebase origin main
remote: Enumerating objects: 27, done.
remote: Counting objects: 100% (27/27), done.
remote: Compressing objects: 100% (17/17), done.
remote: Total 27 (delta 9), reused 18 (delta 8), pack-reused 0
Unpacking objects: 100% (27/27), 11.66 KiB | 8.00 KiB/s, done.
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Successfully rebased and updated refs/heads/ft/bundle-2.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push -u origin main
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because a pushed branch tip is behind its remote
hint: counterpart. Check out this branch and integrate the remote changes
hint: (e.g. 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$ git push -u origin ft/bundle-2
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 2 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.02 KiB | 149.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/new/ft/bundle-2
remote:
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

USER L@NIYO-T MINGW64 ~/vscode (ft/bundle-2)
$
***
## bundle 2

### ex2
***bash

1@DESKTOP-QOH1F4K MINGW64 /d/gymtailwind
$ cd d:/me/gitexercise

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ git bracnch
git: 'bracnch' is not a git command. See 'git --help'.

The most similar command is
        branch

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ git branch
  dev
* main

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ git clone test.html
fatal: repository 'test.html' does not exist

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ git clone https://github.com/indekwe/Gym-Git-Exercise-Solution/blob/main/test.html/services.html.git
Cloning into 'services.html'...
fatal: repository 'https://github.com/indekwe/Gym-Git-Exercise-Solution/blob/main/test.html/services.html.git/' not found

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ git clone https://github.com/indekwe/Gym-Git-Exercise-Solution.git
Cloning into 'Gym-Git-Exercise-Solution'...
remote: Enumerating objects: 39, done.
remote: Counting objects: 100% (39/39), done.
remote: Compressing objects: 100% (27/27), done.
remote: Total 39 (delta 13), reused 26 (delta 10), pack-reused 0
Receiving objects: 100% (39/39), 15.79 KiB | 646.00 KiB/s, done.
Resolving deltas: 100% (13/13), done.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../html.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../...
        ../.gitignore.txt
        ../flexbox/
        ./
        ../js-basics/
        ../navflex/
        ../tailwindcss/
        ../team.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ git log --oneline
3916c30 (HEAD -> main, dev) updated gitnavflex
d703ff1 y git exercise
cd7a24b first commit

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise (main)
$ cd d:/me/gitexercise/Gym-Git-Exercise-Solution

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git pull
Already up to date.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git branch ft/service-redesign

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git add test.html/services.html

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git commit -m "changes in sevices for ex2 bundle2"
[ft/service-redesign c4c0dc8] changes in sevices for ex2 bundle2
 1 file changed, 5 insertions(+)

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git pull origin ft/services-redesign 
fatal: couldn't find remote ref ft/services-redesign

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git push origin ft/services-redesign
error: src refspec ft/services-redesign does not match any
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git push origin main
Everything up-to-date

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git push origin main
Everything up-to-date

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git status
On branch ft/service-redesign
nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git add test.html/services.html

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git commit -m "changes in sevices for ex2 bundle2 second time"
[ft/service-redesign 6a99500] changes in sevices for ex2 bundle2 second time
 1 file changed, 5 insertions(+)

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git push origin ft/bundle-2
error: src refspec ft/bundle-2 does not match any
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git clone https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/1#issue-1718184556
Cloning into '1#issue-1718184556'...
fatal: https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/1#issue-1718184556/info/refs not valid: 
is this a git repository?

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git clone https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/1#issue-1718184556
Cloning into '1#issue-1718184556'...
fatal: https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/1#issue-1718184556/info/refs not valid: 
is this a git repository?

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git push orgin main
fatal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git pull origin main
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * branch            main       -> FETCH_HEAD
Already up to date.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git push origin main
Everything up-to-date

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ <li>
bash: syntax error near unexpected token `newline'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$                         <a href="#">
bash: syntax error near unexpected token `newline'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$                             <span>About</span>
bash: syntax error near unexpected token `newline'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$                         </a>
bash: syntax error near unexpected token `newline'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git branch
  ft/service-redesign
* main

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git switch ft/service-redesign
error: Your local changes to the following files would be overwritten by checkout:
        test.html/services.html
Please commit your changes or stash them before you switch branches.
Aborting

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git commit -m "commit services fourth"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git add test.html/services.html

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git commit -m "services commited fith time"
[main 58e5a3e] services commited fith time
 1 file changed, 13 insertions(+)

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git log --oneline
58e5a3e (HEAD -> main) services commited fith time
a9b4d60 (origin/main, origin/HEAD) Update README.md
f069ee7 Merge pull request #1 from indekwe/ft/bundle-2
1703875 (origin/ft/bundle-2) services commited
ca8766b implement grid layout
9184c11 Update README.md
e584c69 About stash commited
388164d home stash commited
78d1915 need team stash to survive
83a733f need stash about
7653786 this will be stashed
9a47dad Update README.md
973b921 perfect.html gitexercise
5ae1cf2 Initial commit

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 458 bytes | 458.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   a9b4d60..58e5a3e  main -> main

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.html/services.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git add test.html/services.html

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git commit -m "sixth sevice commit"
[ft/service-redesign 45755e5] sixth sevice commit
 1 file changed, 5 insertions(+)

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git status 
On branch ft/service-redesign
nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 1.16 KiB | 397.00 KiB/s, done.
Total 12 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/new/ft/service-redesign
remote:
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git diff

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git log 
commit 45755e5971e31a6e22429e1218f8f8db824c51d8 (HEAD -> ft/service-redesign, origin/ft/service-redesign)Author: indekwe <findekwe@gmail.com>
Date:   Mon May 22 20:02:05 2023 -0700

    sixth sevice commit

commit 6a995009aaaef7943d06f58edd8b8348e76da849
Author: indekwe <findekwe@gmail.com>
Date:   Mon May 22 19:33:39 2023 -0700

    changes in sevices for ex2 bundle2 second time

commit c4c0dc84b124cc2f57e3d271526c8718818c9a67
Author: indekwe <findekwe@gmail.com>
Date:   Mon May 22 19:17:27 2023 -0700

    changes in sevices for ex2 bundle2

commit a9b4d605d596806bef65f662bbbb691c4f8134ba
Author: indekwe <131709694+indekwe@users.noreply.github.com>

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git diff ft/service-redesign

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git diff main
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..e23cf70 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,17 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li>
+                            <span>services and their equivalence</span>
+                        </a>
+                    </li>

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git merge main
Auto-merging test.html/services.html
CONFLICT (content): Merge conflict in test.html/services.html
Automatic merge failed; fix conflicts and then commit the result.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git merge main
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git diff main
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..6924eb2 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,6 +30,19 @@
                     </li>
                     <li>
                         <a href="#">
+<<<<<<< HEAD
+                            <span>services and their equivalence</span>
+                        </a>
+                    </li>
+                    <li>
+                        <a href="#">
+                            <span>services and your will is protected</span>
+                        </a>
+                    </li>
+                    <li>
+                        <a href="#">
+                            <span>services and your survival</span>

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git checkout main
error: you need to resolve your current index first
test.html/services.html: needs merge

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git merge main
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git add .

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git merge main
fatal: You have not concluded your merge (MERGE_HEAD exists).
Please, commit your changes before you merge.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git commit m- "merging services" 
fatal: cannot do a partial commit during a merge.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git commit . m- "merging services"
fatal: cannot do a partial commit during a merge.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git commit --all "merging"
fatal: paths 'merging ...' with -a does not make sense

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git merge main
fatal: You have not concluded your merge (MERGE_HEAD exists).
Please, commit your changes before you merge.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git commit . m- "merging services" 
fatal: cannot do a partial commit during a merge.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git diff main
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git diff main
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
:...skipping...
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
:...skipping...
diff --git a/test.html/services.html b/test.html/services.html
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li>
+
+
:...skipping...
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li>
+
+
+
                         </a>
:...skipping...
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li>
+
+
+
                         </a>
                     </li>
                 </ul>
~
~
(END)...skipping...
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
diff --git a/test.html/services.html b/test.html/services.html
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li>

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git reset
Unstaged changes after reset:
M       test.html/services.html

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git add .

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git commit -m "resolved merging problem"
[ft/service-redesign 6301e67] resolved merging problem
 1 file changed, 3 insertions(+), 11 deletions(-)

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git diff main
diff --git a/test.html/services.html b/test.html/services.html
index 5499155..1212d80 100644
--- a/test.html/services.html
+++ b/test.html/services.html
@@ -30,15 +30,9 @@
                     </li>
                     <li>
                         <a href="#">
-                            <span>services<li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li><li>
-                                <a href="#">
-                                    <span>About</span>
-                                </a>
-                            </li>

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git merge main
Auto-merging test.html/services.html
CONFLICT (content): Merge conflict in test.html/services.html
Automatic merge failed; fix conflicts and then commit the result.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git status
On branch ft/service-redesign
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   test.html/services.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git add .

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        test.html/services.html
Please commit your changes or stash them before you switch branches.
Aborting

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign|MERGING)      
$ git commit -m "conflicts resolved"
[ft/service-redesign 56e9be2] conflicts resolved

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git switch ft/service-redesign
Switched to branch 'ft/service-redesign'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git status
On branch ft/service-redesign
nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git push origin main
Everything up-to-date

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git push origin main
Everything up-to-date

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 862 bytes | 431.00 KiB/s, done.
Total 8 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 3 local objects.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   45755e5..56e9be2  ft/service-redesign -> ft/service-redesign

1@DESKTOP-QOH1F4K MINGW64 /d/me/gitexercise/Gym-Git-Exercise-Solution (ft/service-redesign)
$                   
***bundle 3
             **completed(ex1 and ex2)
                          1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git pull --rebase origin main
remote: Enumerating objects: 46, done.
remote: Counting objects: 100% (46/46), done.
remote: Compressing objects: 100% (30/30), done.
Unpacking objects:  41% (19/46), 3.50 KiB | 6.00 KiB/sremote: Total 46 (delta 17), reused 33 (delta 14), pack-reused 0
Unpacking objects: 100% (46/46), 19.33 KiB | 8.00 KiB/s, done.
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Auto-merging team.html
CONFLICT (add/add): Merge conflict in team.html
error: could not apply 2d7fe99... new team commit
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 2d7fe99... new team commit

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ git status
interactive rebase in progress; onto aeeab52
Last command done (1 command done):
   pick 2d7fe99 new team commit
No commands remaining.
You are currently rebasing branch 'main' on 'aeeab52'.
1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ git add team.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ git branch
* (no branch, rebasing main)
  main

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ 

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ git commit -m "second new team commit"
[detached HEAD 5aa7da3] second new team commit
 1 file changed, 48 insertions(+)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ git push -u origin main
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because a pushed branch tip is behind its remote
hint: counterpart. Check out this branch and integrate the remote changes
hint: (e.g. 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ git pull --rebase origin main
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * branch            main       -> FETCH_HEAD
fatal: It seems that there is already a rebase-merge directory, and
I wonder if you are in the middle of another rebase.  If that is the
case, please try
        git rebase (--continue | --abort | --skip)
If that is not the case, please
        rm -fr ".git/rebase-merge"
and run me again.  I am stopping in case you still have something
valuable there.


1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main|REBASE 1/1)
$ git rebase --continue
Successfully rebased and updated refs/heads/main.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 883 bytes | 883.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   aeeab52..5aa7da3  main -> main
branch 'main' set up to track 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git branch checkout ft/team-page
fatal: not a valid object name: 'ft/team-page'

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git branch ft/team-page

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git branch checkout ft/team-page

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git branch
  checkout
  ft/team-page
* main

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git branch -d checkout
Deleted branch checkout (was 5aa7da3).

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git switch ft/team-page
Switched to branch 'ft/team-page'

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git push -u origin
 *  History restored 


1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ it push -u origin ft/team-page
bash: it: command not found

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git push -u origin ft/team-page
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        ft/team-page -> ft/team-page (fetch first)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git fetch
remote: Enumerating objects: 92, done.
remote: Counting objects: 100% (87/87), done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 78 (delta 33), reused 77 (delta 32), pack-reused 0
Unpacking objects: 100% (78/78), 8.88 KiB | 2.00 KiB/s, done.
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * [new branch]      ft/bundle-2         -> origin/ft/bundle-2
 * [new branch]      ft/service-redesign -> origin/ft/service-redesign
 * [new branch]      ft/team-page        -> origin/ft/team-page

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git status
On branch ft/team-page
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git add team.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git commit -m "team new  commit in ft"
[ft/team-page dc0276c] team new  commit in ft
 1 file changed, 3 insertions(+), 4 deletions(-)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git remote  add origin https://github.com/indekwe/Gym-Git-Exercise-Solution.git
error: remote origin already exists.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git push -u origin ft/team-page
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        ft/team-page -> ft/team-page (non-fast-forward)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git pull --rebase origin ft/team-page
From https://github.com/indekwe/Gym-Git-Exercise-Solution
 * branch            ft/team-page -> FETCH_HEAD
warning: skipped previously applied commit 5ae1cf2
warning: skipped previously applied commit 973b921
warning: skipped previously applied commit 9a47dad
warning: skipped previously applied commit 7653786
warning: skipped previously applied commit 83a733f
warning: skipped previously applied commit 78d1915
warning: skipped previously applied commit 388164d
warning: skipped previously applied commit e584c69
warning: skipped previously applied commit 9184c11
warning: skipped previously applied commit ca8766b
warning: skipped previously applied commit 1703875
warning: skipped previously applied commit a9b4d60
hint: use --reapply-cherry-picks to include skipped commits
hint: Disable this message with "git config advice.skippedCherryPicks false"
Auto-merging test.html/services.html
CONFLICT (content): Merge conflict in test.html/services.html
error: could not apply 58e5a3e... services commited fith time
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 58e5a3e... services commited fith time

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page|REBASE 1/4)
$ git add .

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page|REBASE 1/4)
$ git rebase --continue
[detached HEAD 3b21ffb] services commited fith time
 1 file changed, 12 insertions(+)
Successfully rebased and updated refs/heads/ft/team-page.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git log --oneline
744b5c5 (HEAD -> ft/team-page) team new  commit in ft 
2b89f37 second new team commit
566ebe3 Update README.md
3b21ffb services commited fith time
93795b1 (origin/ft/team-page) third commit team       
78b3e8b second team commit
e2077ad resolved merging problem
22e5297 sixth sevice commit
bb9feb3 changes in sevices for ex2 bundle2 second time
e1575c7 changes in sevices for ex2 bundle2
37b63e2 Update README.md
d946ae1 services commited
0c48d28 implement grid layout
d0ce3e6 Update README.md
6d0d51e About stash commited
90d9b8e home stash commited
ebbc922 need team stash to survive
ed87954 need stash about
d0aaac5 this will be stashed
a331564 Update README.md
6e248b7 perfect.html gitexercise
1aa4bfd Initial commit
50c8c05 new team commit
3916c30 updated gitnavflex
d703ff1 y git exercise
cd7a24b first commit

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git push -u origin ft/team-page
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 4 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (13/13), 5.07 KiB | 648.00 KiB/s, done.
Total 13 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), completed with 4 local objects.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   93795b1..744b5c5  ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git branch ft/contact-page

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git log --oneline
744b5c5 (HEAD -> ft/team-page, origin/ft/team-page) team new  commit in ft
2b89f37 second new team commit
566ebe3 Update README.md
3b21ffb services commited fith time
93795b1 third commit team
78b3e8b second team commit
e2077ad resolved merging problem
22e5297 sixth sevice commit
bb9feb3 changes in sevices for ex2 bundle2 second time
e1575c7 changes in sevices for ex2 bundle2
37b63e2 Update README.md
d946ae1 services commited
0c48d28 implement grid layout
d0ce3e6 Update README.md
6d0d51e About stash commited
90d9b8e home stash commited
ebbc922 need team stash to survive
ed87954 need stash about
d0aaac5 this will be stashed
a331564 Update README.md
6e248b7 perfect.html gitexercise
1aa4bfd Initial commit
50c8c05 new team commit
3916c30 updated gitnavflex
d703ff1 y git exercise
cd7a24b first commit

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git cherry-pick 744b5c5
Auto-merging team.html
[ft/contact-page cb6690e] team new  commit in ft
 Date: Thu May 25 19:29:29 2023 -0700
 1 file changed, 3 insertions(+), 4 deletions(-)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git status
On branch ft/contact-page
nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git status
On branch ft/contact-page
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git add team.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git commit -m "feat:added contact"
[ft/contact-page 6b724d1] feat:added contact
 1 file changed, 5 insertions(+)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git push -u origin ft/contact-page
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 589 bytes | 589.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/new/ft/contact-page
remote:
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git branch ft/faq-page

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git status
On branch ft/contact-page
Your branch is up to date with 'origin/ft/contact-page'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

nothing added to commit but untracked files present (use "git add" to track)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git add faq.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git commit -m "feat:added afq-page"
[ft/contact-page f5a26ef] feat:added afq-page
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git push -u origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 460.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   6b724d1..f5a26ef  ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git log --oneline
f5a26ef (HEAD -> ft/contact-page, origin/ft/contact-page) feat:added afq-page
6b724d1 (ft/faq-page) feat:added contact
cb6690e team new  commit in ft
rrt "feat:add faqrevertedcommit-page"
$ git revert f5a26ef
[ft/contact-page bed02ad] rrt "feat:add faqrevertedcommit-page"
 1 file changed, 12 deletions(-)
 delete mode 100644 faq.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git status
On branch ft/contact-page
Your branch is ahead of 'origin/ft/contact-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git push -u origin ft/contact-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 250 bytes | 250.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   f5a26ef..bed02ad  ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git push -u origin ft/contact-page
Everything up-to-date
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git  add .

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git status
On branch ft/contact-page
Your branch is up to date with 'origin/ft/contact-page'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   faq.html


1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$  git commit -m "faq addedseco "
[ft/contact-page cc226f4] faq addedseco
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git push -u origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 454 bytes | 454.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   bed02ad..cc226f4  ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$ git branch
* ft/contact-page
  ft/faq-page
  ft/team-page
  main

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/contact-page)
$  git checkout ft/faq-page
Switched to branch 'ft/faq-page'

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/faq-page)
$ git branch ft/home-page-redesign

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/faq-page)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Home.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git add Home.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git commit -m "feat: home redesigned "
[main 38154a3] feat: home redesigned
 1 file changed, 1 insertion(+)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git push -u origin main 
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/indekwe/Gym-Git-Exercise-Solution.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git fetch
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 3.47 KiB | 35.00 KiB/s, done.
From https://github.com/indekwe/Gym-Git-Exercise-Solution
   5aa7da3..c5d123e  main       -> origin/main

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git merge
Merge made by the 'ort' strategy.
 README.md | 458 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 458 insertions(+)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$ git push -u origin main
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 589 bytes | 589.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
   c5d123e..0eecaae  main -> main
branch 'main' set up to track 'origin/main'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (main)
$  git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/home-page-redesign)
$ git rebase ft/home-page-redesign
Current branch ft/home-page-redesign is up to date.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Home.html

no changes added to commit (use "git add" and/or "git commit -a")

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/home-page-redesign)
$ git add Home.html

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/home-page-redesign)
$ git commit -m "feat: home redesigned second times "
[ft/home-page-redesign ca53014] feat: home redesigned second times
 1 file changed, 1 insertion(+)

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/home-page-redesign)
$ git push -u origin ft/home-page-redesign
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 901 bytes | 450.00 KiB/s, done.
Total 9 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), completed with 3 local objects.
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/indekwe/Gym-Git-Exercise-Solution/pull/new/ft/home-page-redesign
remote:
To https://github.com/indekwe/Gym-Git-Exercise-Solution.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

1@DESKTOP-QOH1F4K MINGW64 /d/team.html (ft/home-page-redesign)
$
