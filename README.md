# Git

Create a remote repo on a local file system:

```
git init --bare $REPONAME.git
```

Change local trunk branch to main:

```
git branch -m master main
=======
Upgrade Fedora to the next release: 

```
# ensure packages are up to date
sudo dnf upgrade --refresh

# ensure update plugin is installed
sudo dnf install dnf-plugin-system-upgrade

# upgrade!
sudo dnf system-upgrade download --releasever=$VERSION
```
