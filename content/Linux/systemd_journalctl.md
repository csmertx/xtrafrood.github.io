### Cleanup
- sudo journalctl --vacuum-size=50M
- sudov /etc/systemd/journald.conf
- -- #SystemMaxUse=
- ++ SystemMaxuse=50M