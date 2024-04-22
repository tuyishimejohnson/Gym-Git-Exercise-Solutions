ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ ls
about.html  home.html  index.html  README.md  services.html  styles.css

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ ls
about.html  home.html  index.html  README.md  services.html  styles.css

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ git branch
  dev
* ft/bundle-2
  main
  master

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout ft/bundle-2 
Switched to branch 'ft/bundle-2'
Your branch is up to date with 'origin/ft/bundle-2'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ git commit -m "Added services page"
On branch ft/bundle-2
Your branch is up to date with 'origin/ft/bundle-2'.

nothing to commit, working tree clean

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ git push
Everything up-to-date

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/bundle-2)
$ git checkout main 
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 986 bytes | 35.00 KiB/s, done.
From https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions
   448e714..701690d  main       -> origin/main
Merge made by the 'ort' strategy.
 about.html    | 12 ++++++++++++
 home.html     | 11 +++++++++++
 services.html | 12 ++++++++++++
 3 files changed, 35 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ ls
about.html  home.html  index.html  services.html  styles.css

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ git add services.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ git add --all

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ git commit -m "Added some changes to the services page"
[ft/service-redesign 9d3964a] Added some changes to the services page
 1 file changed, 2 insertions(+)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ git push --set-upstream origin ft/service-redesign
Enumerating objects: 13, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 994 bytes | 331.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign     
remote:
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 913 bytes | 83.00 KiB/s, done.
From https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions
   701690d..a4fb540  main       -> origin/main
Updating 8645d87..a4fb540
Fast-forward
 services.html | 2 ++
 1 file changed, 2 insertions(+)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$