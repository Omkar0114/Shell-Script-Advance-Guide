- `/var/log` contains log files of your system.
- `/var/log/messages` contains messages about Contains global system messages, including the messages that are logged during system startup. There are several things that are logged in /var/log/messages including mail, cron, daemon, kern, auth, etc.
- `/var/log/wtmp` contains file tracks logins, logouts, shutdown and reboot events. All audit records will be tagged with the identifier 'session. ' The file /var/log/btmp keeps track of failed login attempts and can be read by entering the command /usr/bin/last -f /var/log/btmp.

- `last -f wtmp` - to read the encoded file "wtmp". Also, show a listing of the last logged-in users.


