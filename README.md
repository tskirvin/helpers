# Skirv's Helper Scripts

Various helper scripts that I use all the time.

These scripts are fairly tied to my specific directory layout (things live
in `~/.config` mostly), but that should be workable enough.

## smux + tmux-session

This pair of scripts wrap autossh and tmux to make it easy to keep
connections open to remote servers even when your connection is flaky.  I
end up running commands like:

    smux hostname.foo.bar remote

...and that `remote` tmux session runs on the remote server for weeks or
months.

