TFClean
=======

Post root Linux assistant - http://basehack.net/member.php?action=profile&uid=49 - http://www.hackforums.net/member.php?action=profile&amp;uid=1789290

--

To compile simply use gcc
gcc TFClean.c -o <name-of-file>

currently cleans:

  /var/log/auth.log
	/var/log/kern.log
	/var/log/cron.log
	/var/log/mail.log 
	/var/log/mysql.log

current commands: 

	clean - to clean the logs
	exit - to exit
	root - uses cronjob method to root

You can also use sh commands, but will not be able to change directories 
