# TowerDefense
A 3D game built in Unity (2017.3.1) where users mut strategically place towers on a grid to prevent enemy bots from reaching the user's base. Players can only place a maximum of three towers by clicking on a legal spot on the grid and can relocate towers at anytime. Towers shoot at the closest enemy bot and enemy bots take the shortest possible route to user's base using the pathfinding algorithm, Breadth First Search.   

Game consists of C# Classes, AI pathfinding (Breadth First Search), data structures (ring buffers, queues, stacks, dictionaries), interactive Unity components (tile map, particle system, waypoint circuit, audio listener, etc), a detailed 3D UI, customised particle effects, coroutines, etc.

## To Build and run

1. Download and install [Unity](https://unity3d.com/get-unity/download/archive?_ga=2.143266357.1615942277.1556738966-578585574.1553552858) (2017.3.1 or newer)
2. Clone/download repo
3. Navigate to `Assets > Levels` then open any `.unity` file
4. Hit Play button 

## Demo
<a href="https://imgflip.com/gif/3066gl"><img src="https://i.imgflip.com/3066gl.gif" width = "500" height = "300"/></a>
