Flappy Bird

STARTING WITH THE Flappy Bird In Python Pygame
Pygame is a set of modules or we can say a library by Python which we use for making games.
There are 4 things important in the Pygame: –

Game Loop
Events
Sprites
Sounds
Game loop is an infinite loop in which we blit our Sprites and play Sounds by handling or accessing Events from the user.

Blitting of the Sprites frequently in a loop gives the illusion to the user that they are playing the game.

However it’s just the game of removing images and blitting new ones, but it happens so fast that’s why our eyes can’t detect it and because of that our sensory nerves make it a game.

After having all this now we can start to code but before that, I also said that I’ll introduce some basic terms that we are going to use in our Game. So, have a look at these terms:-

Function	Description
init()	Initializes all of the imported Pygame modules (returns a tuple indicating success and failure of initializations)
set_mode()	Takes a tuple or a list as its parameter to create a surface (tuple preferred)
update()	Updates the screen
quit()	Used to uninitialized everything
set_caption()	Will set the caption text on the top of the display screen
event.get()	Returns list of all events
time.Clock()	Helps track time
font.SysFont()	Will create a Pygame font from the System font resources
mouse.get_pos()	Returns the coordinates of the Mouse cursor
get_height()	Gives the height of the object
get_width()	Gives the Width of the Object
