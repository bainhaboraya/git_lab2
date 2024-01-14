# How to remove the branches locally and remotely
    To remove the branches locally :

git branch -d dev

    To remove the branches remotely :

git push origin --delete dev

# How to List Tag 
    To list the tags :

    git tag 

# How to Delete tags 
    To delete the tags locally :

git tag -d <tagname>

    To delete the tags remotely :

git push --delete origin <tagname>

     use the “git push” command and specify the tag name 

git push origin :refs/tags/<tag>
```
# README image
![git image ](git-github (1).png)