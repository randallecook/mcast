# mcast
Command-line tools written in Python for sending and receiving messages over
UDP multicast. They can be useful when developing larger systems where
multicast is used as a communication channel.

Invoke each command with no arguments for usage information.

mcast_snd
---------
mcast_snd lets you send a simple message via multicast from the command line to
a group and port.

mcast_rcv
---------
mcast_rcv waits for and displays (on stdout) messages received over multicast
on a specified group and port. Exit with a keyboard interrupt (control-C).

