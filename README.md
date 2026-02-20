# Device Software
Miscellaneous device control software. This repo is a collection of links to device control software repos. Storage of software here as normal is also permitted.

# Included Repos:
Put links to the repos here. Follow this format to copy/paste into bash commands below.

- pressure_gauges/Lesker275_logger/ https://github.com/b-d-doyle/Lesker275_logger.git main

- pressure_gauges/MKS925_serialRead/ https://github.com/b-d-doyle/MKS925_serialRead.git main

- RF_Power_Control/ https://github.com/b-d-doyle/RF_Power_Control.git main

# Instructions:
todo

# Bash Commands:
Add a repo to this repo:
```
git subtree add --prefix=<local-directory> <remote-url> <remote-branch> --squash
```
Get updates from a subtree'd repo (No permissions required):
```
git subtree pull --prefix=<local-directory> <remote-url> <remote-branch> --squash
```
Push updates to a subtree'd repo (Permissions required; only for your own remote repos):
```
git subtree push --prefix=<local-directory> <remote-url> <remote-branch>
```
You can also pull from this repo to your remote repo (I hope. Instructions coming. Maybe.)
