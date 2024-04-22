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
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git commit -m "Updated the readme and services page"
[main 31f88c2] Updated the readme and services page
 2 files changed, 134 insertions(+)
 create mode 100644 README.md

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.55 KiB | 1.55 MiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
   a4fb540..31f88c2  main -> main

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git commit -m "Updated the readme and services page"
[main c100185] Updated the readme and services page
 1 file changed, 2 insertions(+), 3 deletions(-)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 355 bytes | 177.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
   31f88c2..c100185  main -> main

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main
  master

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git add team.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git commit -m "Added team page"
[ft/team-page e5b15a8] Added team page
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 556 bytes | 278.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote:
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git branch ft/contact-page

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/service-redesign
  ft/team-page
* main
  master

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git log
commit e5b15a891c96f3f00f36d20489db4da050231071 (HEAD -> ft/team-page, origin/ft/team-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 19:32:32 2024 +0200

    Added team page

commit c100185d35bc559c92948030f71dadf571fed51e (origin/main, main, ft/contact-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 17:30:27 2024 +0200

    Updated the readme and services page

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'
M       README.md

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$
Display all 5185 possibilities? (y or n)
! 
./
: 
[
[.exe
[[   
]]
___git_complete
__git
__git_aliased_command
__git_checkout_default_dwim_mode
__git_complete
__git_complete_command
__git_complete_common
__git_complete_config_variable_name
__git_complete_config_variable_name_and_value
__git_complete_config_variable_value
__git_complete_fetch_refspecs
__git_complete_file
__git_complete_force_with_lease
__git_complete_index_file
__git_complete_refs

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git
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

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git cherry-pick e5b15a891c96f3f00f36d20489db4da050231071
[ft/contact-page 84369db] Added team page
 Date: Mon Apr 22 19:32:32 2024 +0200
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git add team.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git commit -m "New commit"
[ft/contact-page bb22459] New commit
 1 file changed, 1 insertion(+)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git push --set-upstream origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 796 bytes | 398.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0        
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git branch ft/faq-page

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git branch
  dev
  ft/bundle-2
* ft/contact-page
  ft/faq-page
  ft/service-redesign
  ft/team-page
  main
  master

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/contact-page)
$ git checkout ft/faq-page 
Switched to branch 'ft/faq-page'
M       README.md

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git add faq.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git commit -m "FAQ"
[ft/faq-page dac2704] FAQ
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 550 bytes | 550.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions/pull/new/ft/faq-page
remote:
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git log 
commit dac27047a1a5e749ade3b453e39ca9662500e9dd (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 20:02:35 2024 +0200

    FAQ

commit bb22459afc80a777d62274c79738ece45624bcca (origin/ft/contact-page, ft/contact-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 19:51:47 2024 +0200

    New commit

commit 84369db55e0cc599d76c39dfe1827133930d237b

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git log
commit dac27047a1a5e749ade3b453e39ca9662500e9dd (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 20:02:35 2024 +0200

    FAQ

commit bb22459afc80a777d62274c79738ece45624bcca (origin/ft/contact-page, ft/contact-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 19:51:47 2024 +0200

    New commit

commit 84369db55e0cc599d76c39dfe1827133930d237b

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git log ft/team-page
commit e5b15a891c96f3f00f36d20489db4da050231071 (origin/ft/team-page, ft/team-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 19:32:32 2024 +0200

    Added team page

commit c100185d35bc559c92948030f71dadf571fed51e (origin/main, main)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 17:30:27 2024 +0200

    Updated the readme and services page

commit 31f88c2964afcc09001dea8e050701712e5eb447

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert --continue
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
U       team.html

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git add faq.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git add team.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert --abort

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git commit -m "FAQ"
[ft/faq-page 1c981f7] FAQ
 1 file changed, 271 insertions(+), 1 deletion(-)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.05 KiB | 2.05 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
   dac2704..1c981f7  ft/faq-page -> ft/faq-page

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert --abort

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ ls
about.html  home.html  index.html  README.md  services.html  styles.css  team.html

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git add team.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git commit -m "Team"
On branch ft/team-page
Your branch is up to date with 'origin/ft/team-page'.

nothing to commit, working tree clean

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git push
Everything up-to-date

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git checkout ft/faq-page 
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/faq-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert --skip

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert --skip

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ ls
about.html  home.html  index.html  README.md  services.html  styles.css  team.html

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git log
commit e5b15a891c96f3f00f36d20489db4da050231071 (HEAD -> ft/team-page, origin/ft/team-page)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 19:32:32 2024 +0200

    Added team page

commit c100185d35bc559c92948030f71dadf571fed51e (origin/main, main)
Author: tuyishimejohnson <j.tuyishime4@alustudent.com>
Date:   Mon Apr 22 17:30:27 2024 +0200

    Updated the readme and services page

commit 31f88c2964afcc09001dea8e050701712e5eb447

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/team-page)
$ git checkout ft/faq-page 
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/faq-page'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git add faq.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git commit -m "FAQ"
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

nothing to commit, working tree clean

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git push
Everything up-to-date

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git revert e5b15a891c96f3f00f36d20489db4da050231071
CONFLICT (modify/delete): team.html deleted in parent of e5b15a8 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert e5b15a8... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page|REVERTING)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git commit -m "SOME changes"
On branch ft/faq-page
Your branch is ahead of 'origin/ft/faq-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 340 bytes | 340.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
   8a7e464..1b1a7c4  ft/faq-page -> ft/faq-page

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/home-page-redesign)
$ git checkout main 
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git commit -m "Some changes"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git commit -m "Some changes to the services page"
[main 6b8c789] Some changes to the services page
 1 file changed, 1 insertion(+)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
   c100185..6b8c789  main -> main

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/home-page-redesign)
$ git add home.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/home-page-redesign)
$ git commit -m "Changes to the Homepage"
On branch ft/home-page-redesign
nothing to commit, working tree clean

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/home-page-redesign)
$ git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/home-page-redesign)
$ git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 4 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (16/16), 3.64 KiB | 932.00 KiB/s, done.
Total 16 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign   
remote:
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git remote add git-copy  https://github.com/tuyishimejohnson/git-exercise-2.git

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git add home.html 

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git commit -m "Home"
[main 102c090] Home
 1 file changed, 1 insertion(+)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
   6b8c789..102c090  main -> main

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git push origin
Everything up-to-date

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git push git-copy
Enumerating objects: 47, done.
Counting objects: 100% (47/47), done.
Delta compression using up to 4 threads
Compressing objects: 100% (44/44), done.
Writing objects: 100% (47/47), 8.75 KiB | 597.00 KiB/s, done.
Total 47 (delta 17), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (17/17), done.
To https://github.com/tuyishimejohnson/git-exercise-2.git
 * [new branch]      main -> main

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git commit -m "New branch"
[ft/footer 6854356] New branch
 1 file changed, 1 insertion(+)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git commit -m "second commit"
[ft/footer c7acdba] second commit
 1 file changed, 1 insertion(+), 1 deletion(-)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git push --set-upstream origin ft/footer\
> git push --set-upstream origin ft/footer
error: src refspec ft/footergit does not match any
error: src refspec push does not match any
error: src refspec origin does not match any
error: failed to push some refs to 'https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git'      

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git push --set-upstream origin ft/footer
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 612 bytes | 306.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions/pull/new/ft/footer
remote:
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/footer)
$ git checkout main 
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (main)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/squashing)
$ git merge --squash ft/footer
Updating 102c090..c7acdba
Fast-forward
Squash commit -- not updating HEAD
 home.html     | 2 +-
 services.html | 1 +
 2 files changed, 2 insertions(+), 1 deletion(-)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/squashing)
$ git add .

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/squashing)
$ git commit -m "footer changes squashing"
[ft/squashing c3de090] footer changes squashing
 2 files changed, 2 insertions(+), 1 deletion(-)

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/squashing)
$ git push
fatal: The current branch ft/squashing has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/squashing

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/squashing)
$ git push --set-upstream origin ft/squashing
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 400 bytes | 133.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions/pull/new/ft/squashing
remote:
To https://github.com/tuyishimejohnson/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.

ANNICK'S PC@DESKTOP-IB192KM MINGW64 ~/Desktop/GIT_PROJECT (ft/squashing)
$