## Emacs-connect: A simple shell script for dealing with emacs servers

emacsclient is pretty much the greatest thing since sliced bread, but if you forget
about starting a server (using either emacs --daemon, or M-x start-server) you're sort
of out of luck. emacs-connect just fixes that for you. Invoke emacs always with
emacs-connect, and it'll reuse a previously created emacs --daemon session. If you
have an X windows frame already setup and run M-x start-server (perhaps you already
have this in your init?) then emacs-connect just chooses that frame right away.

## Install it!

    sudo install -m 0755 emacs-connect /usr/local/bin

## Copyright (C) 2009, 2014 Andrew Gwozdziewycz


