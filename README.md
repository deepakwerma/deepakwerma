Microsoft Windows [Version 10.0.26200.7462]
(c) Microsoft Corporation. All rights reserved.

E:\Web Dev\Profile>GIT STATUS
git: 'STATUS' is not a git command. See 'git --help'.

E:\Web Dev\Profile>GIT INIT
git: 'INIT' is not a git command. See 'git --help'.

E:\Web Dev\Profile>git init
Initialized empty Git repository in E:/Web Dev/Profile/.git/

E:\Web Dev\Profile>git add .

E:\Web Dev\Profile>git istatus
git: 'istatus' is not a git command. See 'git --help'.

The most similar command is
        status

E:\Web Dev\Profile>git add .

E:\Web Dev\Profile>git commit -m"add code"
[master (root-commit) e4d1721] add code
 1 file changed, 15 insertions(+)
 create mode 100644 REadme.MD

E:\Web Dev\Profile>git branch main

E:\Web Dev\Profile>git branch
  main
* master

E:\Web Dev\Profile>git branch -D main
Deleted branch main (was e4d1721).

E:\Web Dev\Profile>git branch
* master

E:\Web Dev\Profile>git branch -m master main

E:\Web Dev\Profile>git remote add origin https://github.com/deepakwerma/deepakwerma.git

E:\Web Dev\Profile>git push origin
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


E:\Web Dev\Profile>git push -u origin main
To https://github.com/deepakwerma/deepakwerma.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/deepakwerma/deepakwerma.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

E:\Web Dev\Profile>
E:\Web Dev\Profile>
