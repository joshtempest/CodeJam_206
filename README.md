# CodeJam
The game, Space Game is made by Frederik Larsen, Emil Carstensen, Joshua Bussink, Mathias Claus Hagedorn & Mathias Nygaard Laursen.

Emil Carstensen made the ObejctMovement and contributed to everything else and made the GameManager and scenes.
Frederik Larsen made the BulletScript, PlayerShooter and the SoundManager.
Joshua Bussink made the SpawnManager.
Mathias Claus Hagedorn made the PlayerMovement.
Mathias Nygaard Laursen made the Sprites, normal maps, Health script, ammo script, setup the render pipeline and lighting and contributed to everything else.



- Improvements
I have implemented a shield pickup, to do that I have made changes in the following scripts:
	- SpawnManager to actually spawn the pickup
	- ObjectMovement to get the pickup to interact with the player
	- Health so the shield prevents one instance of damage to the player