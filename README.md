SSH Key-based Authentication
=============================

By default, this package cannot access your SSH keys. If you want key-based authentication to work, you'll need to apply some overrides:

```bash
flatpak override --user --filesystem=~/.ssh --filesystem=$SSH_AUTH_SOCK org.mosh.mosh
```
