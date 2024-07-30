1//
# To remove (dev,test) branches locally
git branch -d dev
git branch -D test

# To remove (dev,test) branches remotely
git git push origin :dev
git git push origin --delete test

_________________________________________________

2// 
# Checkout another branch without commit changes
ggit stash
git checkout "Branch name"
git stash pop  

__________________________________________________

3// 
# How to list tags
git tag

__________________________________________________

4// 
# To delete Tags locally
git tag -d tagName

# To delete Tags remotely
git push origin :tagName
git push origin --delete tagNamegit 
___________________________________________________

![Git Logo](./Git-Icon-1788C.png)



