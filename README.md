# Santa Run

### Project description: 
This is a simple 2D side-scroll game. The Santa runs from left to right and has to avoid some obstacles by jumping over them.
The game ends when the Santa hits an obstacle.  The goal is to avoid as many obstacles as possible.

### Development platform: 
Windows 10, Unity version 2019.1.14f1, Visual Studio Community 2017, Scripting Runtime Version: .NET 4.0

### Target platform: 
WebGl and Standalone, RefRes: 1920 * 1080


### Visuals: 
<div>
<img src = "./Screenshots/sketch-SantaRun.JPG" width = "500">
</div>

<iframe width="560" height="315" src="https://www.youtube.com/embed/2C74XxBkFfI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[![SANTA RUN](http://i.imgur.com/Ot5DWAW.png)](https://www.youtube.com/embed/2C74XxBkFfI "Santa RUN")

### Necessary setup/execution steps: 
For playing the game go to: 
* WebGL: https://hs-teaching.github.io/WegGL-SantaRun/
* Standalone (.exe): Clone project and publish as Standalone

For development: Clone this project. 

### Third party material: 
* This game is based on the game Santa Run developed by Raja Biswas in the Udemy-course Unity 2018 Game Developmen by Example 
[Unity 2018 Game Development by Example](https://www.udemy.com/course/unity-2d-game-development-by-example/).
* Sprites are used from https://www.gameart2d.com/santa-claus-free-sprites.html


### Project state: 
Program is working correctly, no errors, refactoring is needed.
Refactoring needed: 
* del not used namespaces
* del unused variables
* del needless debugs
* del needless comments
* del unused methods
* rename variables (coding standards)
* rename methods (coding standards)
* fix poor conditional clauses
* fix poor formating
* replace magic string
* replace magic number

### Limitations: 
Only one level is implemented. 

### Lessons Learned: 
* Create 2D Scenes
* Use Quads for moving Backgrounds (Textures instead of Sprites)
* Use Particle System for snowing effect.
* Use Scene Management for switching between Scenes
* Create and control Animations (Animation, Animator and Scripts)
* Use the singelton pattern
* Spawn objects
* Use UI elements and manipulate UI elements with scrips


Copyright by smeerws
