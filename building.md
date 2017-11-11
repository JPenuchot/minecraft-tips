# Building

##### Villager farm

Just build the following :

```
Top view :

[D][D][D][D][D][D][D][D][D][D][D][D][D]
[D][#][#][#][#][#][#][#][#][#][#][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][.][.][.][.][X][.][.][.][.][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][.][.][.][.][.][.][.][.][.][#][D]
[D][#][#][#][#][#][#][#][#][#][#][#][D]
[D][D][D][D][D][D][D][D][D][D][D][D][D]

[#] = 2 block high wall
[D] = Door
[.] = Crops
[X] = Water with a block on it
```

Make sure it's under **direct sunlight** or your villagers won't reproduce. You can build other farms and link them to extend your village efficiently and easily. Also iron golems will spawn so that's pretty cool.

##### Chicken farm

You can make a simple ckicken farm that repeatedly throws eggs in a breeding place and gather new eggs from the newly born ckickens etc. over and over again, but your population would grow exponentially and at some point it might crash the server you're playing on.

To avoid that, make the breeding and egg laying zone separate.

Here's what it looks like :

```
Side view :

[ ][ ][ ][ ][ ][ ][ ]
[#]->           <-[#]  <--  Top part where eggs are laid
[#][#][#][V][#][#][#]       (laying zone)
         [>]   [#]     <--  Eggs should be shot on the wall
          i 
[REDS]___[#]
[#][#][#]

[#]->           <-[#]  <--  Bottom part where ckickens are bred
[#][#][#][V][#][#][#]       (breeding zone)

[#]     =  Stone block
[ ]     =  Glass pane
[V]     =  Hopper
[>]     =  Dispenser
 i      =  Redstone torch
[REDS]  =  Redstone triggering system
->      =  Water flow


Top view of the laying zone zone :

[ ][ ][ ][ ][ ][ ][ ]
[ ][W]         [W][ ]
[ ]               [ ]
[ ]      [V]      [ ]
[ ]               [ ]
[ ][W]         [W][ ]
[ ][ ][ ][ ][ ][ ][ ]

[ ] =  Glass pane
[V] =  Hopper
[W] =  Water
```

The water is meant to keep the ckickens inside the laying zone so they don't escape and push laid eggs inside the hopper.