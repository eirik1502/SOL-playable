# SOL-playable

The game "Smash of Legends" playables. That is, runnable jar's (runnable, packed, compressed java).

## Getting Started

### Installing

Every release comes with three programs (jars).
 - *Server* (The program running on one of the players computer)
 - *Client* (The program running on every players computer)
 - *Offline* (Not the actual game, just a version running without a server to see the game)

Download all of them by downloading *the-game* folder as a zip.
You can also download the individual programs if you go into the folder.

(If you want an older version of the game, you can explore the other archives)

Unpack the downloaded zip, and put the three files in a convenient location (f.ex. in your user folder).


### Running the game

One player has to run the *server* program.
All players (including the one running the server) has to run the client program.
In the clients, specify the IP-address of the server. *To find the ip-address*:
  1. the player running the server should head to CMD (or anoher command window)
  2. type "ipconfig"
  3. read the address of "IPv4 Address". It has a format similar to "xxx.xxx.xxx.xxx"
  4. let every player write this address, and push "enter"
  (5. The player running the server don't need to type the address, just press enter ("localhost" is then recognized).)

### Playing the game

Play!
How to will come

## Built With

* [LWJGL](https://www.lwjgl.org/) - GLFW, OpenGL and OpenAL binding for java
* [OpenGL](https://www.opengl.org/) - A low level graphics library
* [OpenAL](https://www.openal.org/) - A low level sound library
* [GLFW](https://www.glfw.org/) - A OpenGL library for creating windows and handling input

## Authors

* **Harald Vinje** - *Co-developer* - [HaraldVinje](https://github.com/haraldvinje)
* **Eirik Skjærseth** - *Co-developer* - Me


## Acknowledgments

* Thanks to Blank (norwegian IT consultancy) for giving us a scholarship to create this.
* Inspired by [Super Smash](https://www.smashbros.com/en_US/) and [League of Legends](https://play.eune.leagueoflegends.com/en_PL)
