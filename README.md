# tmux.conf
tmux config for legacy users

## introduction
I know tmux rocks **in new versions**, however, a lot of servers with tmux version <= 1.8 were installed. 

I only need a very small subset of the features of tmux, so I picked out some config lines from [https://github.com/gpakosz/.tmux](https://github.com/gpakosz/.tmux) which I am using on my personal computer.

For details of the config you can forward to [https://github.com/gpakosz/.tmux](https://github.com/gpakosz/.tmux).

## installation

### wget
```
wget -o ~/.tmux.conf https://raw.githubusercontent.com/lovelock/tmux.conf/main/tmux.conf
```

### curl
```
curl -O ~/.tmux.conf https://raw.githubusercontent.com/lovelock/tmux.conf/main/tmux.conf
```

> I don't know who would like to use git to install it with the two methods above available, so no need to provide it.
