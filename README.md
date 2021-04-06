#### Homework Assignment 1 for CMPE 279

=== Notes ===

For some reason, all of my commits show up as authored by user *Charlie Root*.  This might be because of how I configured my git credentials and my git remotes.

I commented out `SO_REUSEPORT` in the `setsockopt` function call because it is an unsupported protocol as of OpenBSD 6.8

=== Usage ===

Build

```powershell
$ git clone <repository>
$ cd cmpe279
$ make
```

Run

```powershell
$ ./server &
$ ./client
```

Clean

```powershell
$ make clean
```
