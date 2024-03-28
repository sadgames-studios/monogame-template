# monogame-template
Monogame Template
Welcome to our Monogame Template! From here we can perform several functions to develop our game.
If you don't have any information about Monogame, here is a link to the official Monogame documentation: https://monogame.net/documentation/

This will be only our game, it does not contain Herarchy, Inspector, Console etc, for this, we will use our IDE `Sad Engine`, which you can download from our repo : https://github.com/sadgames-studios/sadengine

We will have some basic scripts: 
1) Restore
2) Build
3) Run

All these scripts can be launched from our mg_build_run.sh file, which will do all 3 commands.
This can be adapted to your project.

## MonoGame 
Monogame Base Project.
This project will be the starting point of our game.
It contains:
1) Camera
2) Transform
3) Scene System
4) Entity System
5) Layouts System

## ImGui
<p>This project uses ImGui to render our UI in our game, read implementation about LayoutSystem for more information.</p>
<p>A new `editor` project is added which will be linked in our Monogame, it will have all references to __ImGui__.</p>
