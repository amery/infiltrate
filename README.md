Infiltrate the interactions between a tty and a serial port or
an interactive tool.

## Purpose
* logging
* replay
* expect/send
* automation
* ...

## Signals

SIGTERM
: pass-through as signal or close

SIGINT
: pass-through as signal or control sequence

SIGHUP
: pass-through as signal or close

SIGCHLD
: -- via cmd.Wait()

SIGWINCH
: resize pts and pass-through signal or send _(XTerm)_ control sequence

## References

* [ANSI escape code](http://en.wikipedia.org/wiki/ANSI_escape_code)
* [ECMA-048](http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-048.pdf)
* [XTerm Control Sequences](http://invisible-island.net/xterm/ctlseqs/ctlseqs.html)
