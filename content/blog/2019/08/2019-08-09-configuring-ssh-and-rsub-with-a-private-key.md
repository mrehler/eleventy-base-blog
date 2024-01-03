---
title: "Configuring SSH and rsub Without a Config File"
date: "2019-08-09"
categories: 
  - "personal"
  - "technology"
---

I picked up an AWS Lightsail instance to play with while trying to learn a few things for personal hobbies. I’ve really taken to using Sublime Text, and one of my favorite features may be `rsub`. `rsub` piggy-backs off of a technology developed for TextMate called `rmate`. While BBEdit is able to open an entire FTP directory, and of course FTP clients are able to open whatever editor you please, there are times it’s nice to be able to launch into editing directly from a shell.

I got the basic setup from [Keyrus](http://blog.keyrus.co.uk/editing_files_on_a_remote_server_using_sublime.html) for installing `rmate` on my Lightsail server. Briefly, it’s:

```
sudo wget -O /usr/local/bin/rsub https://raw.github.com/aurora/rmate/master/rmate
sudo chmod +x /usr/local/bin/rsub
```

`rsub` is installed locally through Package Control for Sublime Text.

Unfortunately, I’ve had some issues with my SSH config file, so I was unable to get `rsub` to tunnel back. If you follow the instructions on the [linked post](http://blog.keyrus.co.uk/editing_files_on_a_remote_server_using_sublime.html), you wouldn’t have to deal with this. I, however, needed to establish this in my ssh startup command (loaded into the iTerm profile for my Lightsail instance).

I got the answer on fixing the tunnel from [Stack Overflow](https://stackoverflow.com/questions/37458814/how-to-open-remote-files-in-sublime-text-3), using the bind address option. On top of that, I declare the identity file of my private key in the SSH command[\[1\]](1 "see footnote") when I’m loading the server, and I wasn’t sure immediately what order to handle those in.

The final command was:

```
ssh -R 52698:localhost:52698 -i FILEPATHTOPRIVATEKEY username@instance.url
```

Loaded in that manner, I can just load text files using `rsub` with ease.

I wanted to share this just to lay out the solution for anyone dealing with the same thing, and because I haven’t had an excuse to post in awhile. None of this would be hard to figure out for anyone doing this on a serious basis, but that doesn’t describe me at all.

* * *

1. This should also be done in the SSH config file. After trying to configure SSH in Sourcetree with Github, I started having issues SSHing elsewhere through iTerm and deleting the config file solved all of those problems. I have no idea what I’m doing.  [↩](1 "return to article")
