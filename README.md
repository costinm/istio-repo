# Experimental manifests for using Istio with Gerrit/Repo

This project maintains manifest to automate and simplify the download of Istio 
and its dependents. This includes istio projects, envoy and its dependencies, as well
as a generated vendor directory and 'flat build' tools.

It also includes few experiments on building with cmake for non-official platforms.

See [Repo documentations](https://source.android.com/source/using-repo) for details on using repo.
This is only using repo for multiple git repository download - gerrit is not yet setup.

```
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo

# -b BRANCH for a specific branch
repo init -u https://github.com/costinm/istio-repo

repo sync -c
# To reproduce a specific build:
# repo sync -c -m snapshot.xml

```



# Links/notes

https://stackoverflow.com/questions/14331754/creating-a-default-manifest-for-git-repo
http://www.instructables.com/id/Using-Googles-repo-command-in-your-own-projects/



