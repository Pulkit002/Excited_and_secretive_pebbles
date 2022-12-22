# Excited_and_secretive_pebbles
Excited and secretive pebbles contains a grid of 10 rows and columns with each pebble just being a circle with a border.

Within the grid, the pebble at 7th column and 7th row ([6][6] if you index from 0) is the secret pebble (sP). Every pebble in the 7th column [:][6], 7th row [6][:] and diagonal from [0][0] to [9][9] will point towards this pebble (shifting up, down, left, right) and with some sort of shadow in the appropriate direction. Furthermore, an off-center, slightly tilted diagonal from the other two corners ([0][9] and [9][0]) will also point to sP. All these direction pebbles will get a slight coloration when they are hovered over as well.

All pebbles including sP (except those with special directions to point to) will simply vibrate in their spot upon hovering. Nothing should happen when any pebble other than sP is clicked. When sP is clicked, it should change color and display two messages on either side.
