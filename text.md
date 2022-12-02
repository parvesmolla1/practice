Windows PowerShell

Try the new cross-platform PowerShell https://aka.ms/pscore6

* main
PS C:\jhonkars\practice> git branch added-image
PS C:\jhonkars\practice> git branch
  image-add
* main
PS C:\jhonkars\practice> git checkout added-image
Switched to branch 'added-image'
PS C:\jhonkars\practice> git branch
* added-image
  image-add
  main
PS C:\jhonkars\practice> git commit -m "images added"
[added-image 895941f] images added
 2 files changed, 1 insertion(+)
 create mode 100644 pic-3.png
PS C:\jhonkars\practice> git push
fatal: The current branch added-image has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin added-image

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\jhonkars\practice> git push --set-upstream origin added-image
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'added-image' on GitHub by visiting:
remote:      https://github.com/parvesmolla1/practice/pull/new/added-image
To https://github.com/parvesmolla1/practice.git
 * [new branch]      added-image -> added-image
PS C:\jhonkars\practice> git branch
* added-image
  main
PS C:\jhonkars\practice> git merge main
Already up to date.
* added-image
  main
PS C:\jhonkars\practice> git checkout main
Your branch is up to date with 'origin/main'.
PS C:\jhonkars\practice> git checkout added-image
Switched to branch 'added-image'
PS C:\jhonkars\practice> git branch
* added-image
  main
PS C:\jhonkars\practice> git merge added-image
PS C:\jhonkars\practice> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
  added-image
  image-add
* main
PS C:\jhonkars\practice> git checkout added-image
Switched to branch 'added-image'
Your branch is up to date with 'origin/added-image'.
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\jhonkars\practice> git branch
  image-add
PS C:\jhonkars\practice> git merge added-image
Fast-forward
 index.html |   1 +
 pic-3.png  | Bin 0 -> 52876 bytes
 2 files changed, 1 insertion(+)
PS C:\jhonkars\practice> git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/parvesmolla1/practice.git
   70a7f14..895941f  main -> main
PS C:\jhonkars\practice> git pull
Already up to date.
PS C:\jhonkars\practice> git pull
Already up to date.
PS C:\jhonkars\practice> git oull
git: 'oull' is not a git command. See 'git --help'.

        pull
PS C:\jhonkars\practice> git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 738 bytes | 36.00 KiB/s, done.
From https://github.com/parvesmolla1/practice
Updating 895941f..3262207
Fast-forward
 index.html | 4 ++--
gti : The term 'gti' is not recognized as the name of a cmdlet, function, script file, or operable program. Check    
At line:1 char:1
+ gti branch
+ ~~~
    + FullyQualifiedErrorId : CommandNotFoundException
PS C:\jhonkars\practice> git branch
  added-image
* main
PS C:\jhonkars\practice> git branch -d image-add
PS C:\jhonkars\practice> git branch
  added-image
  img-blog
PS C:\jhonkars\practice> git branch -d img-blog
Deleted branch img-blog (was 3262207).
PS C:\jhonkars\practice> git branch
  added-image
* main
PS C:\jhonkars\practice> git checkout img-blog
error: pathspec 'img-blog' did not match any file(s) known to git
PS C:\jhonkars\practice> git checkout -b img-blog
PS C:\jhonkars\practice> git branch
  added-image
* img-blog
  main
PS C:\jhonkars\practice> git push
fatal: The current branch img-blog has no upstream branch.
To push the current branch and set the remote as upstream, use
    git push --set-upstream origin img-blog

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\jhonkars\practice> git commit -m "new blog"
On branch img-blog
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
no changes added to commit (use "git add" and/or "git commit -a")
PS C:\jhonkars\practice> git status
On branch img-blog
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

PS C:\jhonkars\practice> git add .
PS C:\jhonkars\practice> git commit -m "blog create"
[img-blog 0e20a00] blog create
 1 file changed, 5 insertions(+)
PS C:\jhonkars\practice> git push
fatal: The current branch img-blog has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin img-blog

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\jhonkars\practice> git push --set-upstream origin img-blog
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 475 bytes | 237.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'img-blog' on GitHub by visiting:
remote:      https://github.com/parvesmolla1/practice/pull/new/img-blog
remote:
To https://github.com/parvesmolla1/practice.git
 * [new branch]      img-blog -> img-blog
branch 'img-blog' set up to track 'origin/img-blog'.
PS C:\jhonkars\practice> 