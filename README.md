# Mumtris

This is a Tetris game in MUMPS, for GT.M V5.x and MUMPS V1, have fun.

Resize your terminal (e.g. maximize your PuTTY window), restart GT.M so that it can report true size of your terminal, and d ^mumtris.

For MUMPS V1 see convert-mv1. Use "size" environment variable to enable large terminal support.

The default cursor positioning is ANSI escape code based, as it a little bit faster than standard GT.M USE $P:(X=x,Y=y). Switch back to GT.M standard by setting ansi=0 in mumtris routine if the screen gets messy.

*NOTICE: Mumtris uses "active waiting" for making delays lower that 1s. That means that one of your CPU will be used at 99%. It's not a bug, the Mumtris and GT.M will be fully responsive. Take care when running on production system ;-)*
