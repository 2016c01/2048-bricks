```
# 2048-bricks
A new game by 2016c01
After continuous efforts, a new game is completed on my computer.
It's a classic game,and I played 260 thousand +.
Before play it, read the introduction first.

# The original introduction:

Ketchapp-2048 bricks

You will play the game in a 5×7 game box.
The square will fall automatically, and you can only slide around to make the box merge.

For example:

    ↓Current block
0 0 2 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 2 0 0

If you click the screen, it will automatically drop to the bottom.
just like this:
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 2 0 0
0 0 2 0 0

Then find the adjacent squares and merge them, and add the score of the merged block.

0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0    +4
0 0 0 0 0
0 0 4 0 0
0 0 0 0 0

And then fall by "gravity".

0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 0 0 0
0 0 4 0 0

When there are more than 2 adjacent squares, a higher level square will be synthesized.
For example:
       ↓Current block
 0  0 32  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0 32  0  0  0
 0128 32  0  0
 0512256  0  0

When you click the screen, the current block will fall to the bottom.

 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0 32 32  0  0
 0128 32  0  0
 0512256  0  0
 
And then merge with adjacent squares.

 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0    +128(2 blocks ×2;3 blocks ×4;4 blocks(max) ×8)
 0  0128  0  0
 0128  0  0  0
 0512256  0  0
 
 Fall...
 
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0128128  0  0
 0512256  0  0
 
 Once again.
 
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0    +256
 0  0  0  0  0
 0  0256  0  0
 0512256  0  0

 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0    +512
 0  0  0  0  0
 0  0512  0  0
 0512  0  0  0

 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0  0  0  0  0
 0512512  0  0

until..

 0  0   0  0  0
 0  0   0  0  0
 0  0   0  0  0
 0  0   0  0  0    +1024
 0  0   0  0  0
 0  0   0  0  0
 0  01024  0  0

Adaptation

Because is's too difficult for me to make automatic drop.(I'm so vegetable)

So players are asked to drop manually, which gives players a lot of benefits.

Maybe your score will be higher than me qwq

Others should be retained according to the original (if there is any mistake, please point out.)
```
