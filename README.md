# SEI-Project-One

// challenging to get pacman to stop at walls, pacman stopped at walls but could not walk again, so ended up using classes to prevent the movement
// making enemmies move was a challenge too, I first started by storing all the ghosts current positions in one Node list, and using .forEach method to update ghost position. 
// I ended up breaking down the problem by writing one enemy in an object and writing a function similar to that of keydown for player
// when this worked, i tried making this function reusable so i could pass all the ghosts as arguments and use the same function
// after making all enemies move, i still have to refine the enemy movement so they move at random rather than follow a set if / else if statement, I could not understand the logic behind their movement so decided to work on other parts of the game and come back to it later
// making special mode come to fruition: break it down into smaller more manageable tasks like adding timeOut function, testing the function with console.log...
// making the start and end screen was an interesting process as it turns out it was mainly about css and html reformating, where i first thought i needed to write more javascript functions for it
// after adding more styling and layout, adding responsive design, I went back to the ghostmove function and was able to make the ghosts chase pacman, using pacmancurrentposition and width in my conditions. I broke the grid into two columns, and asked the ghosts to detect in what column pacman was. This allowed me to work out their potential movement closer to pacman and its current position.
This is still a broad approximation of pacmancurrent position but has the effect of making the ghosts chase pacman