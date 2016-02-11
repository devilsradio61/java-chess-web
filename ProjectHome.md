# Overview #

java-chess-web is an implementation of the game of chess written in Java, with a front end Ajax web application.  The motivation for starting this app was to allow me to practice TDD on a non-trivial application, and have a little fun doing it.

A live demo of this project is available at http://www.brasee.com/games/lobby.htm.  The current release supports human vs. human games from multiple clients or a within a single browser.  A chess lobby provides access to the multiplayer games and chat functionality for all users. Future releases may include the possibility of playing against an AI opponent, if I'm feeling really adventurous.

All of the source code for this project is available for examination or personal use.  It is implemented in Java 6, and checked in with the necessary files to set up a workspace in Eclipse 3.5 and deploy to a Tomcat 6.0.18 server.

The Subversion stream does not contain the necessary JAR files, but the featured download is a .zip file containing all the code and libraries for the current release.

# Releases #

### 0.3.1 - September 26th, 2009 ###
Fixed a bug where the "Watch Game" link wouldn't display for a multiplayer game with both white and black players assigned.

### 0.3.0 - September 25th, 2009 ###
Multiplayer gameplay has been implemented, and the lobby now provides a point of access to the games, as well as the ability to chat with other users.

### 0.2.0 - June 11th, 2009 ###
The chess lobby chat room has been completed, which will provide the interface for players to start and join multiplayer games in the next release.

### 0.1.0 - May 27th, 2009 ###
This is the first iteration of java-chess-web.  The game logic has been completed, as well as a basic Ajax interface allowing human vs. human games from a single client.