A simple framework written in [Erlang](http://www.erlang.org/) for building concurrent 2D games. Uses an object-oriented design for structuring your game as lots of processes running simultanously. This was built as a third year project at the [University of Kent](http://cs.kent.ac.uk).

# Features #
  * Allows your game to automatically be updated in parallel.
  * Uses OpenGL for hardware accelerated graphics.
  * whilst also using a pipelining structure so drawing happens at the same time as updating.

Uses hardware accelerated graphics using OpenGL and the Erlang WX bindings.

# Install #
  * Download the current version from the [downloads](http://code.google.com/p/erlworld/downloads/list) page.
  * Extract the contents to the 'lib' folder in your Erlang install.

# Examples #
Currently three simple examples built using the framework which you can find in the downloads section. All games include source code.

## Blastox ##
An asteroids clone showing that the framework can handle a complete (although small) game. Press space to shoot and use the arrow keys to control the player. The aim is to stay alive are asteroids fade into space which you must destroy to gain points.
![http://erlworld.googlecode.com/svn/trunk/docs/blaxtox_screen.png](http://erlworld.googlecode.com/svn/trunk/docs/blaxtox_screen.png)

To play call 'blastox:start()' from erlang.

## Circles ##
Starts out empty, but click to add circles. They fly out according to the direction your moving will bounce around the world.
![http://erlworld.googlecode.com/svn/trunk/docs/circles_screen.jpg](http://erlworld.googlecode.com/svn/trunk/docs/circles_screen.jpg)

To play call 'circles:start()' from erlang.

## Pong ##
It's not a game engine if it doesn't have a Pong clone. You play on the left, computer on the right.
![http://erlworld.googlecode.com/svn/trunk/docs/pong_screen.png](http://erlworld.googlecode.com/svn/trunk/docs/pong_screen.png)

To play call 'pong:start()' from erlang.