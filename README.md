# SmartMirror
A smart mirror is a two-way mirror with an electronic display behind the glass. The display can show the viewer different kinds of information in the form of widgets, such as weather, time, date and news updates.
This project involves the development of a smart mirror powered by a raspberry pi running some custom scripts. It uses MichMich's brilliant MagicMirror module which provides complete control.

MagicMirror focuses on a modular plugin system and uses Electron as an application wrapper. So no more web server or browser installs necessary!

Two aspects of this project:
 1. Hardware:
    We converted an old VGA monitor into a two way mirror by attaching a glass to the screen with tint foiled applied on it which gave the     glass a reflective finish.
    All of the code runs on the RPi connected to the display.
 2. Software:
    We tweaked the config files of the RPi so that it never goes to sleep, and intstalled MagicMirror on it. After developing some modules     which we wanted to be displayed on the Mirror, it was ready :) 
