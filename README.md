SSH Key-based Authentication
=============================

By default, this package cannot access your SSH keys. If you want key-based authentication to work, start ssh-agent outside flatpak and add override:

```bash
flatpak override --user --socket=ssh-auth org.mosh.mosh
```

Note that flatpak 1.0.0 or higher is required.
