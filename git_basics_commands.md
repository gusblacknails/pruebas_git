#Git Basics

##Init a repository

To initialize a repositori we have to use the `git-init`
This command will create a hidden `.git` subfolder in the project folder.

Si se hace un `git commit` sin el `-m` osea sin mensaje entrará al editor de textos por comando del mac. Para salir tendremos que apretar `esc + :` aparecerán dos puntos al final de la pantalla. Apretamos `q` para salir.

First time files are *untracked* 
To start tracking our files we have to `commit` them.
To `commit` the  files we have to do the following...
For example, if we have an `index.html` created we can start tracking it by doing:
```
git init
git add index.html
git commit -m "first commit"
```
