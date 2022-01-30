# trek
## Trek(6) port for POSIX Systems from OpenBSD
This is a Linux/POSIX compatible port of trek(6) the infamous Star Trek command line game in its C version
written by Eric Allman for 1BSD.
Actually port is a little far fetched as it's already pretty POSIX conformant execpt for some OpenBSD specifics.
## Requirements
- Needs ` libm.so ` for its rather complex arithmetic
## Building
Run `autoconf && ./configure` and it should take care of the rest.
