# Project Summary
This project will be a multiplayer "tetris" game in which two players compete against one another over a local network. It will be a client server application pair that communicate to keep users' clients up to date on the current state of the match. 

# Problem
There is no problem to solve per se, there are plenty of other good multiplayer "tetris" games out there, but it would be an interesting and fun challenge to see what goes into the development of a game with networking features.

# Features
- Required Goals
	- The ability to play in a one versus one "tetris" match against another player on a LAN (e. g. the UTK network)
	- The ability to see your own "tetris" board and a preview of the opponenet's board at the same time (the opponent's client sends information about their piece placements to the server and the server sends them back to you)
	- Custom user profiles with usernames and tuning settings so your username shows up when you connect to a server and the opponent can see it.
	- Modern Tetris guideline standards
	- Basic graphics, no sound
- Stretch Goals
	- The ability to connect to a server and spectate an ongoing match
	- Singleplayer modes
	- Basic text chat functionality
	- Sounds
	- (Relatively) Fancy Graphics
	- Cusomizable game settings on the server

#Tools
- Python3
	- Pygame
	- Sockets
	- Threads
- Online Pygame tutorials and source code (**HEAVILY** modified)
- Online socket servers tutorials

# Who would use this?
People who want to play tetris with friends on the net and would like to host their own server.

# Final note
I use "tetris" in this proposal because the Tetris Company is very stringent about use of their trademark, the actual program would not use any Tetris branding.