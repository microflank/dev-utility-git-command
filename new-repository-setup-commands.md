#How to remove a git remote url
git remote remove origin

#How to change git remote URI (URL) instead of removing and adding a new one
git remote set-url origin new.git.url/here

#adding a new remote URI (URL) on a fresh repository
step 1:git remote add origin yourRemoteUrl
step 2:git push -u origin main
