Created by: Isaac Chan and Kenneth Li
How to use: Make a clone of this repo and then open the main folder, trashPokemon, using Greenfoot

![Title Screen Preview](images/TitleScreen.png?raw=true "Preview")

------------------------------------------------------------------------
Things I would change: The file structure could use some work, putting them all into a source file folder
would have been helpful for organization.
------------------------------------------------------------------------
Asset Credits:
- Cavern tileset by Adam Saltsman: https://adamatomic.itch.io/cavernas
	- Maps were manually built using this tileset

- Chest, coin and heart by Startled Pixels: https://startledpixels.itch.io/2d-pixel-item-asset-pack

- Player by rvros: https://rvros.itch.io/animated-pixel-hero

- 16-bit spike (seen in tutorial spike image) by Omniclause: https://omniclause.itch.io/spikes
	- Spike used in tileset was made manually to fit 8x8 tile

- Main game BGM by Florian Stracker: https://florianstracker.itch.io/the-heros-path-free-16bit-adventure-game-music

- Win/Lose music from Final Fantasy II

Sorting:
- You can find the sorting algorithm (MergeSort) in the Utilities class at the bottom

- Actual call for the method is in the Scores world subclass

Scores:
- Scores should save on reset as long as code is not modified

- Scores delete when GreenFoot is closed

Sidenote:
- If the music ever does not work or causes the game to crash, etc
	- Disable music in Win/Lose screens and in TitleScreen
	- This a known issue with Greenfoot's sound file decoders

- Game would have been better compressed if mp3s actually worked with Greenfoot
	- .wav works much better and has fewer errors

