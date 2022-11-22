Week 10

To Compile:
gcc hanoi.c -o hanoi -lm

TO run:
./hanoi

* This week we solved The Tower of Hanoi is a puzzle game.
* Only one disk may be moved at a time.
* Each move consists of taking the upper disk from one of the rods and sliding it onto another
rod, on top of the other disks that may already be present on that rod.
* No disk may be placed on top of a smaller disk.       
* If n = 1, then we simply need to move the disc from rod 1 to rod 3.
* If n > 1, then we want to move n − 1 discs from rod 1 to rod 2 (using rod 3 as an intermedi-
ary), which leaves disc n alone on rod 1. Move that disc from rod 1 to rod 3. Finally, move
the n − 1 discs from rod 2 to rod 3, using rod 1 as an intermediary.
