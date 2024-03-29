# cub3d

First-person 3D representation of a maze using raycasting, similar to Wolfenstein 3D (1992).

### Prerequisites

The project runs using the MiniLibX, a simplified version of the Xlib. It can therefore only run in MacOSX, preferably on a computer with a solid CPU !

### The game

Just like B.J. Blazkowicz in Wolfenstein 3D, you have infiltrated a nazi stronghold.

<p align="center">
  <img src="https://i.imgur.com/ll5P9RN.png" width="60%" />
</p>

### Controls

You can move around the maze with ``W`` ``A`` ``S`` ``D``.

You can also rotate the view with the directional arrows ``←`` and ``→``.

You can shoot/stab with ``SPACE`` and open doors with ``SHIFT``.

To exit the game, press ``ESC`` or click the red cross.

### The mandatory part

The basic program that was required to pass. It only includes wall textures and a sprite ; no floor/ceiling textures, no weapons, no enemies, no game elements at all.

<p align="center">
  <img src="https://i.imgur.com/Vf1HLRE.png" width="60%" />
</p>

### How to run it (mandatory part only)

Using ``make`` will make and run the mandatory part.

You can also use ``make`` to generate the ``cub3D`` executable. You can launch it with ``./cub3D``.

### Controls (mandatory part only)

Controls are the same as the project with bonuses, but only ``W`` ``A`` ``S`` ``D`` to move and ``←`` ``→`` to turn are available.
