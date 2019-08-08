# Lugi

An old mainframe game, ported to GNU Pascal.

The original source is found here:
https://github.com/PDP-10/sri-nic/blob/master/files/src/games/lugi.pas

This version compiles with GNU Pascal, and it doesn't crash on start-up, but
that's about all I have tested.

Differences:

- I disabled the high score system, since that code was completely
  non-portable.

- On the original system, players would not have seen the initialization
  messages. The game assumed some sort of dump/undump functionality, which
  modern operating systems do not provide.

Other than that, the code barely required changes.
