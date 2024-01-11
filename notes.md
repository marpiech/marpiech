# System setup
Edit `sudo visudo /etc/sudoers`
```
Defaults    env_keep+=SSH_AUTH_SOCK
marpiech    ALL=(ALL:ALL) NOPASSWD: ALL
```
