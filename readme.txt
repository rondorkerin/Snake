#####################################################

Snake!
By Stephen Bryant
December 04, 2010

######################################################

Thanks for downloading my snake game!
To build it you must link the allegro game libraries..
http://www.talula.demon.co.uk/allegro/

then you can compile with gcc with the following command
gcc snake.c `allegro-config --libs`. Feel free to take the
source code and do what you will with it.. it's mostly 
aggregated from tutorials.

The game uses tiles, and it draws them inefficiently.
Every frame, it draws every possible tile. The resolution
is 640x480, the tile_size is 20, and the map_width is 32,
map_height is 24. The snake is implemented as a link-list
of nodes. I use a recursive function to move the snake.
Overall, it's a pretty nifty idea! I don't know how everyone
else implements snake, but this worked for me!

I hope this game helps you guys learn allegro.
It was my first one, so I can't say it's a very good example.
Send all suggestions for improvement to sbryant31@knights.ucf.edu
