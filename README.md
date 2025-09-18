# One .config to rule them all

## Setup
```console
$ cd .config
$ git init
$ git remote add origin git@github.com:ikansazov/.config.git
$ git fetch origin
$ git reset --hard origin/master
```
## FAQ
Q: Why not just git clone?\
A: Most likely you already have .config directory that is not empty.

Q: Will `git reset --hard origin/master` overwrite my current configs?\
A: It will overwrite only tracked configs by this repo.
