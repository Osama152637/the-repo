1-
local:
 *git branch -d dev
 *git branch -d test
remotly:
*git push origin :dev
*git push origin :test

2- by stashing changed files using git stach then pop these files by using git stash pop  when back again changed branch

3- git tag

4-
local:  git tag -d v1.7
remotly:  git push origin :v1.7

![Logo](images.jpg)
