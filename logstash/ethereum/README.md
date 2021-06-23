To change `/var/log/messages` permissions to 644:
- add `$umask 0000` after `#### RULES ####` in `/etc/rsyslog.conf`
- move old `messages` file anywhere
- restart rsyslog by `sudo systemctl restart rsyslog.service`