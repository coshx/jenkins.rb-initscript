jenkins.rb-initscript
=====================

The debian-compatible jenkins startup script adapted for [jenkins.rb](https://github.com/cowboyd/jenkins.rb) (and [RVM](https://rvm.beginrescueend.com)).

Instructions
------------

1.  Copy `jenkins.init` to `/etc/init.d/jenkins`
2.  `sudo chmod +x /etc/init.d/jenkins`

Tested on Ubuntu 10.10 with a default jenkins.rb install (UNIX user jenkins, gemset jenkins, ruby ree).
