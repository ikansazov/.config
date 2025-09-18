# One .config to rule them all

## Setup 
$ cd .config
$ git init
$ git remote add origin git@github.com:ikansazov/.config.git
$ git reset origin/master
$ git fetch
$ git checkout -t origin/master

## FAQ
Q: Why not just git clone?
A: Most likely you already have .config directory that is not empty.
