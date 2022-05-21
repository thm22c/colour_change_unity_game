# colour_change_unity_game
My first attempt at an Unity game

# desired gameplay
As seen in the demo-rendering
While the timer on the side runs out, the player picks on of the colors on the bottom of the screen.
Then his hexes all assume the same color. Any adjacent hexes of the same color as the new one, now are also his.
His hexes start in the upper left corner, and the CPUs in the upper right, taking turns at changing colors.

## status
- Models done
- timer & animation & parameters for timer done
- click-listener on object done
- playingfield generator todo
- menu todo

## what did not work so far
- 2d non-sprite geometry -> can only be applied in fixed-update and even then is glitchy
- 3d mesh in a 2d scene

-> so in general i will abandon the procidural hexgeneration and 2d project in favor of a 3d project with fixed camera and have hand-modeled meshes in the prefabs and have a script pull it into the game-area.
