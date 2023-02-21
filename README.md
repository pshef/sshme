# sshme

Have you ever wanted to make connecting to a host through ssh take longer?
Are you tired of typing `less ~/.ssh/config` to see what hosts you have?
Well, sshme then!

This is probably only useful if you have a ton of ssh hosts saved, but I thought it would be fun and I wanted to try writing something using [gum](https://github.com/charmbracelet/gum). As I'm building out a home lab (see the gif for a preview of where it lives), I will be needing ssh to be on more and more devices so wanted to give this a shot.

I have my ssh config set up in the same format for every entry, and so I wrote it based on that. If you have it written a different way, this might not work but is only really based on the `Host <whatever>` part which should be the first line of each entry.

## Requirements
This requires you have gum installed and in your `$PATH`. I installed it via go.

## GIF
![](https://github.com/pshef/sshme/blob/main/sshme.gif)
