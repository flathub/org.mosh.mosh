SSH Key-based Authentication
=============================

By default, this package can only access SSH keys in actual home through ssh-agent. If you do not wish to use ssh-agent,
suggestion is to drop keys under .var/app/org.mosh.mosh/.ssh/. Note that these keys will be fully accessible by the app
since you need to pass app password to decrypt them.
