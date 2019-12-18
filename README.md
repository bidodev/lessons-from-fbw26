# lessons


* git
#### SSh Key 
[Github](https://help.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

* github

#### New repo 

```
echo "# YOUR-REPO-NAME" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:YOUR-ACCOUNT/YOUR-REPO.git
git push -u origin master

```

#### upstream 
If the original repository would update often and you want to get those updates from time to time, then instead of editing origin it would be best to add a new remote:
```
$ git remote rename origin upstream
$ git remote add origin http://github.com/YOU/YOUR_REPO
```

Then, whenever you want to get changes from upstream, you can do:

```
$ git fetch upstream
```
new line
