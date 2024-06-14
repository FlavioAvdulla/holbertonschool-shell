# Permissions

The Unix-like operating systems, such as Linux differ from other computing systems in that they are not only *multitasking* but also *multi-user.*

What exactly does this mean? It means that more than one user can be operating the computer at the same time. While a desktop or laptop computer only has one keyboard and monitor, it can still be used by more than one user. For example, if the computer is attached to a network, or the Internet, remote users can log in via [ssh](http://linuxcommand.org/lc3_man_pages/ssh1.html) (secure shell) and operate the computer. In fact, remote users can execute graphical applications and have the output displayed on a remote computer. The X Window system supports this.

The multi-user capability of Unix-like systems is a feature that is deeply ingrained into the design of the operating system. If we remember the environment in which Unix was created, this makes perfect sense. Years ago before computers were "personal," they were large, expensive, and centralized. A typical university computer system consisted of a large mainframe computer located in some building on campus and *terminals* were located throughout the campus, each connected to the large central computer. The computer would support many users at the same time.

In order to make this practical, a method had to be devised to protect the users from each other. After all, we wouldn't want the actions of one user to crash the computer, nor would we allow one user to interfere with the files belonging to another user.

This lesson will cover the following commands:

- [chmod](http://linuxcommand.org/lc3_man_pages/chmod1.html) - modify file access rights
- [su](http://linuxcommand.org/lc3_man_pages/su1.html) - temporarily become the superuser
- [sudo](http://linuxcommand.org/lc3_man_pages/sudo8.html) - temporarily become the superuser
- [chown](http://linuxcommand.org/lc3_man_pages/chown1.html) - change file ownership
- [chgrp](http://linuxcommand.org/lc3_man_pages/chgrp1.html) - change a file's group ownership

