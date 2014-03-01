# rfc5766-turn-server

rfc5766-turn-server 3.2.2.8 Standard Edition compiled for Ubuntu 12.0.4 Precise Pangolin as found here:

https://code.google.com/p/rfc5766-turn-server/

This is an apt repository.

It can be cloned locally and referred to directly:

    git clone https://github.com/sous/rfc5766-turn-server-precise
    ( echo deb file://`pwd`/rfc5766-turn-server-precise precise main
      echo deb-src file://`pwd`/rfc5766-turn-server-precise precise main ) > /etc/apt/sources.list.d/rfc5766-turn-server-precise.list

Either way, the gpg key for this repo can be imported using:

    curl https://raw.github.com/sous/rfc5766-turn-server-precise/master/apt-key.gpg | sudo apt-key add

Alternatively, this is codified in this chef cookbook: https://github.com/sous/rfc5766-turn-server-cookbook

