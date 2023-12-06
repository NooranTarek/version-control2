# version control lab2
<html></br></html>

![1](https://image.slidesharecdn.com/gitrepo-191003071449/75/understanding-git-and-version-control-1-2048.jpg?cb=1668634411)

<html></br></html>
1-Create a new project on your local machine,then push it your remote repo.
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v1.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v2.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v3.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v4.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v5.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v6.png?raw=true)

<html></br></html>
2-Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo.

<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v7.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v8.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v9.png?raw=true)
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v10.png?raw=true)

<html></br></html>
3-Merge this changes on Master branch and then push it to your remote master branch.
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v11.png?raw=true)
<html></br></html>
4-Tell me how to remove them locally and remotely.
<html></br></html>
Remove Branches Locally:
<html></br></html>

git checkout master
git branch -d dev
git branch -d test
<html></br></html>

Remove Branches Remotely:
<html></br></html>

git push origin --delete dev
git push origin --delete test

<html></br></html>
5-Create an annotated tag with tagname (v1.7).
<html></br></html>
6-Push it to the remote repository.
<html></br></html>

![1](https://github.com/NooranTarek/version-control2/blob/master/version%20control%20lab2/v12.png?raw=true)
<html></br></html>
7-Tell me how to list tags.
<html></br></html>
git tag
<html></br></html>

8-Tell me how to delete tag locally and remotely.
<html></br></html>
Delete Tag Locally:
<html></br></html>
git tag -d tagName
<html></br></html>

Delete Tag Remotely:
<html></br></html>

git push origin --delete tagName

