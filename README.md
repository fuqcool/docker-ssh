## Install

Add following script to .bashrc or .zshrc

```
export fpath=(/path/to/docker-ssh $fpath)

autoload docker-ssh
autoload _docker-ssh
compdef _docker-ssh docker-ssh
```
