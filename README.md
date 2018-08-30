# Agario-HTML5
Agar.io clone written with Socket.IO and HTML5 canvas 
A simple but powerful Agar.IO built with socket.IO and HTML5 canvas on top of NodeJS.

Game Basics

    Move your mouse around the screen to move your cell.
    Eat food and other players in order to grow your character (food respawns every time a player eats it).
    A player's mass is the number of food particles eaten.
    Objective: Try to get as big as possible and eat other players.

Gameplay Rules

    Players who haven't eaten yet cannot be eaten as a sort of "grace" period. This invincibility fades once they gain mass.
    Everytime a player joins the game, 3 food particles will spawn.
    Everytime a food particle is eaten by a player, 1 new food particle will respawn.
    The more food you eat, the slower you move to make the game fairer for all.
    
Installation

You can simply click one of the buttons below to easily deploy this repo to Bluemix or Heroku:

Requirements

To run / install this game, you'll need:

    NodeJS with NPM installed.
    socket.IO.
    Express.

Downloading the dependencies

After cloning the source code from Github, you need to run the following command to download all the dependencies (socket.IO, express, etc.):

npm install

Running the Server

After downloading all the dependencies, you can run the server with the following command:

npm start

The game will then be accessible at http://localhost:3000 or the respective server installed on. The default port is 3000, however this can be changed in config.

FAQ

    What is this game?

This is a HTML5 of the game <a href="https://sites.google.com/site/playfrivgame/agario">Agario</a>. Someone said that Agar.IO is a clone of an iPad game called Osmos, but we haven't tried it yet. (Cloneception? :P)

    Why would you make a clone of this game?

Well, while the original game is still online, it is closed-source, and sometimes, it suffers from massive lag. That's why we want to make an open source version of it: for educational purposes, and to let the community add the features that they want, self-host it on their own servers, have fun with friends and more.

    Any plans on adding an online server to compete with Agar.IO or making money out of it?

No. This game belongs to the open-source community, and we have no plans on making money out of it nor competing with anything. But you can of course create your own public server, let us know if you do so and we can add it to our Live Demos list!

    Can I deploy this game to my own server?

Sure you can! That's what it's made for! ;)

    I don't like HTML5 canvas. Can I write my own game client with this server?

Of course! As long as your client supports WebSockets, you can write your game client in any language/technology, even with Unity3D if you want (there is an open source library for Unity to communicate with WebSockets)!

    Can I use some code of this project on my own?

Yes you can.
