### What is C?

`C` is a small Python3 script which trying to imitate `ctrl` or `cmd` key for files operation. How it works? It's simply like this:

```shell
$ cd /etc
$ c c passwd
+. /etc/passwd
$ c c sudoers sshd_config
+. /etc/sudoers
+. /etc/sshd_config
$ cd ~/backup
$ c v
Copying to `/home/gekoreed/backup'
. /etc/sshd_config -> backup/sshd_config
. /etc/passwd -> backup/passwd
. /etc/sudoers -> backup/sudoers
``````
