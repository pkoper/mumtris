# Mumtris

This is a tetris game in MUMPS, for GT.M, have fun.

Resize your terminal (e.g. maximize your PuTTY window), restart GT.M so that it can report true size of your terminal, and d ^mumtris.

*NOTICE:* Mumtris uses "active waiting" for making delays lower that 1s. That means that one of your CPU will be used at 99%. It's not a bug, the Mumtris and GT.M will be fully responsive. Take care when running on production system ;-)

<pre>

                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . |
           [#]           | .  .  .  .  .  .  .  .  .  . | SCORE: 0
           [#][#][#]     | .  .  .  .  .  .  .  .  .  . | LEVEL: 1
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  . [#][#] .  .  .  .  . |
                         | .  .  . [#][#] .  .  .  .  . | MOVE: LEFT, RIGHT
                         | .  .  .  .  .  .  .  .  .  . | TURN: UP
                         | .  .  .  .  .  .  .  .  .  . | DROP: SPACE
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . | FILL: F
                         | .  .  .  .  .  .  .  .  .  . | GRID: G
                         | .  .  .  .  .  .  .  .  .  . | HELP: H
                         | .  .  .  .  .  .  .  .  .  . |
                         | .  .  .  .  .  .  .  .  .  . | QUIT: ESC, Q
                         | .  .  .  .  . [#] .  .  .  . |
                         | .  .  .  .  . [#][#][#] .  . |
                         |~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~|

</pre>
