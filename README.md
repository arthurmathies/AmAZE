#aMaze

**aMaze** is a simple maze game harnessing the power of [**lanterna**](https://code.google.com/p/lanterna/). **Lanterna** is a console text GUI library for Java or as it says on their page: *"Lanterna is a Java library allowing you to write easy semi-graphical user interfaces in a text-only environment, very similar to the C library curses but with more functionality."*

**aMaze** is an ASCII terminal-based application that benefits from many of Javas features including automatic garbage-collection and object orientation.

##Features

####Menu
The menu gives the player the ability to choose between different difficulty levels, start previously saved games or quit the application all together.

![](https://github.com/arthurmathies/aMaze/blob/master/images/mainMenu.png)

####Gameplay
Levels are randomly generated to give the player a new experience every time. The choosen difficulty level determines different variables in the creation of the game including number of monsters and density of the field.

![](https://github.com/arthurmathies/aMaze/blob/master/images/gameplayEasy.png)

The goal is very simple: Collect a key and reach an exit point while at the same time avoiding being eaten by a monster on your way there. But do not worry you have three lives just in case something goes wrong.

![](https://github.com/arthurmathies/aMaze/blob/master/images/gameplay.png)

The game includes static(in turquoise) and attacking monsters(in red). The screen automagically changes when you walk out of the currently rendered part of the maze.

At any point you can also save the game and exit the game, look at the key or go back to the main menu.

##Usage
Make a build(.jar) and start playing or start the game right from inside your favourite IDE.

##Dependencies
* [lanterna 2.1.7](https://code.google.com/p/lanterna/downloads/detail?name=lanterna-2.1.7.jar&can=2&q=)
* [Java SE 8](https://java.com/de/download/) or newer

##License
MIT &copy; [Arthur Mathies](https://github.com/arthurmathies) 





