# Git Intro

> > > > > > 
> **Git is a _DVCS_ file system made of snapshots** and no need for network connection to 
> complete the work, it gets the informations from the local disk. all changes are tracked 
> `extremly difficlt to lose data`
> > > > > >


```
git config --list `to check settings`

git command --help `to get help`

git stash `to stash files and hide changes`

git stash apply `to retrieve hidden changes`

```

___________________________________________________________

# Remote Repositories

> Teams can use remote repos to push and pull data from,
> they also can view all specified remote handles 


### Cloning a repo

Git automatically give a name _origin_ and abranch name _main_ for any cloned repo.




```
git clone [link of repository]

git remote -v `to check remote handels` 
```

___________________________________________________________

# Workflow 

**from server to local disk**

#### life cycle of file status 

![file_status_life_cycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)


and we can use `git status` for a status check

as for pushing a file we need to use the three pushing steps `phases` as follow 

```
git add `name of the file or (dot) for all files in the directory`

git commit -m "write what you changed in the files"

git push `pushing cahnges to remotes`

```

