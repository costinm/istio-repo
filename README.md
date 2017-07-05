# Experimental manifests for using Istio with Gerrit/Repo

```
repo init -u https://github.com/costinm/istio-repo

repo sync -c
repo sync -c -m master.xml

mkdir cmake-build-debug


mkdir cmake-build-pi

```



# Links/notes

https://stackoverflow.com/questions/14331754/creating-a-default-manifest-for-git-repo
http://www.instructables.com/id/Using-Googles-repo-command-in-your-own-projects/

Project copyfile: src project relative, dest relative to top of tree.
Allows 'patching' a project as it is checked out.
Also 'linkfile' creates a symlink.


