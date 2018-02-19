# git-github-remote
git-github-remote

git init
git remote add orgin "https://github.com/richan2014/git-github-remote.git"
git pull
git status
git add
git add -A // add all files
git commit -m "message"          // adding one file
git commit -a -m "add all files" // adding all files which are already added before

// create a new file into the new branch

// switch back to the master branch and you don't see the new files
git checkout master

// merge local branch back to the master
// on the master branch
git checkout master
git merge {branch_name} 
git merge firstbranch

// Rebase

git pull // pull all the changed files into master branch = fetch and merge
git fetch // 

// Go back to master
240  git checkout master
241  git rebase firstbranch

git@github.com:richan2014/git-github-remote.git  // ssh
https://github.com/richan2014/git-github-remote.git

ssh-keygen

$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/richan/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/richan/.ssh/id_rsa.
Your public key has been saved in /c/Users/richan/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:LsKnCHCOpQTdvGpScwkGs4ny6gleIpnGn25bbhIaP68 richan@T460SHD3R8
The key's randomart image is:
+---[RSA 2048]----+
|o                |
|.* o             |
|* + o            |
|oo . o           |
|..* +   S        |
|+% *   .         |
|@+B.+.o .        |
|*==*+= .         |
| ++EOo           |
+----[SHA256]-----+

richan@T460SHD3R8 MINGW64 /c/tutorial2/git-github-remote (master)
$ cat /c/Users/richan/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCu7iO4rnOUypOQ/nMuOLGBzpz0i1FMLeQIAThUsDUjb17doqMts8S9isPPQxhb4fdQNPaIwa87E7T3BFgm
tWry0Ns6ZqYxiTzHq/P16+E95EYPkOz0NaJ1RLdUyxBrjP5Ib1aBxY1Dxr0KEhP61zaZCEbae1agHMiT8kNdXRUXjJKaFWQnU+gJs2wD78vG5owljiiOleNL
QGpkb2f92bFj5J4B1goyl7N2xzM4NpdU4a0f7y6l2yaA5ESFbmv6E02viY8lpOZr9wkNnsWIfC5hmGLtXATUUwHobBLSc18x83Yn3JnhLnOmnlKm3jgRpTOD
7Ee8y5czIVlI9PgsOPYr richan@T460SHD3R8


git checkout firstbranch
git push orgin firstbranch

$ git push orgin firstbranch
Counting objects: 28, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (23/23), done.
Writing objects: 100% (28/28), 2.54 KiB | 519.00 KiB/s, done.
Total 28 (delta 10), reused 0 (delta 0)
remote: Resolving deltas: 100% (10/10), done.
To https://github.com/richan2014/git-github-remote.git
 * [new branch]      firstbranch -> firstbranch







