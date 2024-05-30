# Bash

`sed` in specific files, e.g. AAA for BBB in yaml files:

```
find . -type f -name "*.yaml" -exec sed -i 's/AAA/BBB/g' {} +
```

# Git

Create a remote repo on a local file system:

```
git init --bare $REPONAME.git
```

Change local trunk branch to main:

```
git branch -m master main
```

# Fedora

Upgrade to the next release:

```
# ensure packages are up to date
sudo dnf upgrade --refresh

# ensure update plugin is installed
sudo dnf install dnf-plugin-system-upgrade

# download the upgrade
sudo dnf system-upgrade download --releasever=$VERSION

# finally, go for it!
sudo dnf system-upgrade reboot
```
# MacOS

Finder to show all files

```
defaults write com.apple.Finder AppleShowAllFiles true
```
