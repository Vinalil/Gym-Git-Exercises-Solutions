# Git exercise project

this project will be used for a series of git exercises

### bundle 3
### exercise 1
...bash
Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git branch ft/team-page

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git add branch ft/team-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
fatal: pathspec 'branch' did not match any files       

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git checkout ft/team-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/team-page'

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git add team.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git commit -m "team page"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/team-page 7d506b8] team page
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/team-page
nothing to commit, working tree clean

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page        

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git push --set-upstream origin ft/team-page 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 456 bytes | 456.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0   
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Vinalil/Gym-Git-Exercises-Solutions/pull/new/ft/team-page
remote:
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page      
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git checkout main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git branch ft/contact-page

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git checkout ft/contact-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/contact-page'

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git checkout ft/team-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.  

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git log
commit 7d506b8046f42dfe028855f27981f0d1a2af1811 (HEAD -commit 7d506b8046f42dfe028855f27981f0d1a2af1811 (HEAD -> ft/team-page, origin/ft/team-page)
Author: vinalil <njongilyvine@gmail.com>
Date:   Sat May 27 05:03:39 2023 +0300

    team page

commit f69175900ed1648ae5a5c4f41b8ed565c5acf128 (origin/ft/service-redesign, ft/service-redesign)
Author: vinalil <njongilyvine@gmail.com>
Date:   Sat May 27 04:54:14 2023 +0300

     read new change

commit ce989426268723027fd1c6224aca6c6b640ccc7a        
Merge: cebbef1 8585f9a
Author: vinalil <njongilyvine@gmail.com>
Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/team-page)
$ git checkout ft/contact-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/contact-page'

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git cherry-pick 7d506b8046f42dfe028855f27981f0d1a2af1811
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/contact-page bbf8b20] team page
 Date: Sat May 27 05:03:39 2023 +0300
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git add --all
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git add contact.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git commit -m "contact page"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/contact-page d291736] contact page
 1 file changed, 13 insertions(+)
 create mode 100644 contact.html

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page     

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$  git push --set-upstream origin ft/contact-page 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 784 bytes | 784.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0   
remote: Resolving deltas: 100% (2/2), done.
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Vinalil/Gym-Git-Exercises-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git branch ft/faq-page

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/contact-page)
$ git checkout ft/faq-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/faq-page'

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/faq-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

nothing added to commit but untracked files present (use "git add" to track)

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git add faq.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git commit -m " the faq"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/faq-page 8f933ad]  the faq
 1 file changed, 13 insertions(+)
 create mode 100644 faq.html

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$  git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 467 bytes | 467.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0   
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Vinalil/Gym-Git-Exercises-Solutions/pull/new/ft/faq-page
remote:
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page        
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git log
commit 8f933ad32d4811cc792b230f4bb013c059b52df8 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: vinalil <njongilyvine@gmail.com>
Date:   Sat May 27 05:38:45 2023 +0300

     the faq

commit d2917360238a2a93833f2d94a7ef83c7408a986f (origin/ft/contact-page, ft/contact-page)
Author: vinalil <njongilyvine@gmail.com>
Date:   Sat May 27 05:30:56 2023 +0300

    contact page

commit bbf8b20aef1736c1a914ec5a7ba637c251d397ff        
Author: vinalil <njongilyvine@gmail.com>
Date:   Sat May 27 05:03:39 2023 +0300

    team page

commit 8585f9ad031431f129c6f6eb35db76822f1a7d97 (origin
/main, main)
Author: vinalil <njongilyvine@gmail.com>
Date:   Sat May 27 04:25:13 2023 +0300

    changes on sercvice

commit 6c88f7d09ec9ab7e2628508779a385c4aed1dd60        
Author: vinalil <njongilyvine@gmail.com>
Date:   Sat May 27 04:17:03 2023 +0300

    new service paragraphy

commit bb265a70004e965bf1076e87d63592783045cf49 (test) 
Author: Samiskina <mureraksamantha@gmail.com>
Date:   Fri May 19 21:27:54 2023 +0300

     adding home page

commit 47d38699ca55eab199e08b3e458c80c380ad32b6        
Author: Samiskina <mureraksamantha@gmail.com>
Date:   Thu May 18 21:26:15 2023 +0300

    init project
    Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)                          d2917360238a2a93833f2d94a7ef83c7408a986f 83c7408a986f   
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Unstaged changes after reset:
D       contact.html

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git revert 7d506b8046f42dfe028855f27981f0d1a2af1811  
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
hint: Waiting for your editor to close the file...   
Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 ! [rejected]        ft/faq-page -> ft/faq-page (non-fast-forward)
error: failed to push some refs to 'https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/faq-page
Your branch is behind 'origin/ft/faq-page' by 1 commit, and can be fast-forwarded.
  (use "git pull" to update your local branch)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)    
        deleted:    team.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    contact.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html


Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 ! [rejected]        ft/faq-page -> ft/faq-page (non-fast-forward)
error: failed to push some refs to 'https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 ! [rejected]        ft/faq-page -> ft/faq-page (non-fast-forward)
error: failed to push some refs to 'https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git pull ft/faq-page
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
fatal: 'ft/faq-page' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights    
and the repository exists.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git pull main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights    
and the repository exists.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git pull origin main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
From https://github.com/Vinalil/Gym-Git-Exercises-Solutions
 * branch            main       -> FETCH_HEAD
Already up to date.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 ! [rejected]        ft/faq-page -> ft/faq-page (non-fast-forward)
error: failed to push some refs to 'https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git pull --rebase origin main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
error: cannot pull with rebase: You have unstaged changes.
error: additionally, your index contains uncommitted changes.
error: please commit or stash them.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git add faq.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git commit -m " faq"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/faq-page aa72e70]  faq
 1 file changed, 3 insertions(+), 2 deletions(-)       
 rename team.html => faq.html (74%)

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git add --all
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git commit -m " change"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/faq-page f78e410]  change
 1 file changed, 13 deletions(-)
 delete mode 100644 contact.html

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 ! [rejected]        ft/faq-page -> ft/faq-page (non-fast-forward)
error: failed to push some refs to 'https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git pull --rebase origin main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
From https://github.com/Vinalil/Gym-Git-Exercises-Solutions
 * branch            main       -> FETCH_HEAD
Current branch ft/faq-page is up to date.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/faq-page)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.
