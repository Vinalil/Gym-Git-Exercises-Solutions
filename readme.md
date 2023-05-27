# Git exercise project

this project will be used for a series of git exercises

### bundle 2
### exercise 2
... bash
Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git branch main
fatal: a branch named 'main' already exists

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git checkout -b main
fatal: a branch named 'main' already exists

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git switch main
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'main'

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git add service.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git commit -m "new service paragraphy"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[main 6c88f7d] new service paragraphy
 1 file changed, 22 insertions(+)
 create mode 100644 service.html

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
nothing to commit, working tree clean

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git push --set-upstream origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 776 bytes | 776.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0   
remote: 
remote: Create a pull request for 'main' on GitHub by visiting:
remote:      https://github.com/Vinalil/Gym-Git-Exercises-Solutions/pull/new/main
remote:
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git add service.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git commit -m "changes on sercvice"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[main 8585f9a] changes on sercvice
 1 file changed, 1 insertion(+), 1 deletion(-)

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0   
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
   6c88f7d..8585f9a  main -> main

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (main)
$ git switch ft/service-redesign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch ft/service-redesign
Your branch is up to date with 'origin/ft/service-redesign'.

nothing to commit, working tree clean

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git checkout ft/service-redesign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Already on 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git diff <ft/service-redesign> <main>
bash: syntax error near unexpected token `<'

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git diff ft/service-redesign main
diff --git a/service.html b/service.html
diff --git a/service.html b/service.html
index ef6c9c6..bf0cff9 100644
--- a/service.html
index ef6c9c6..bf0cff9 100644
--- a/service.html
+++ b/service.html
@@ -15,7 +15,8 @@
        <li> service 3</li>
     </ul>
     <li><a href=#>About</a></li>
-    <li><a href=#>contact</a></li>
+    <li><a href=#>contact us</a></li>
     <li><a href=#>home</a></li>
+    <p>The love of God we hold in our self is so powerful than we can imagine. let's pray hard to embrace it, inorder to bring peace and happinness with full of joy that is what is really needed in this earth of full of suprise. to be ready for that we need that holly spirit strengths to strengthen us.</p>
 </body>
 Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git merge main to ft/service-redesign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
merge: to - not something we can merge

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git merge main ft/service-redesign
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Auto-merging service.html
CONFLICT (add/add): Merge conflict in service.html     
Automatic merge failed; fix conflicts and then commit the result.

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign|MERGING)
$ git commit -m " merge service"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[ft/service-redesign ce98942]  merge service

Samantha@LAPTOP-S1C40SCM MINGW64 ~/Dropbox/PC/Desktop/njongi exercise (ft/service-redesign)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 279 bytes | 279.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0   
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Vinalil/Gym-Git-Exercises-Solutions.git
   cebbef1..ce98942  ft/service-redesign -> ft/service-redesign
   ...