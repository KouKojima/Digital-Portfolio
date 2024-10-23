# Digital-Portfolio
## A Puzzle game
**Solo**<br>
**Tool: Unity Blender. Language: C# HLSL**<br>
**Time cost: 1.5 month**<br>
I wrote a 3d Puzzle game in Unity.<br>
![image](game.png)<br>
In this game, you can throw the block into the door and it will pop out on the other side of the door.<br>
Similarly, this mechanism can disguise a non-Euclidean space.<br>
To learn more about my game, you can watch the [video](gamedemo.mp4) <br>
## Software Renderer
**Solo**<br>
**Tool: Visual Studio Code. Language: JAVA**<br>
**Time cost: 1.5 month**<br>
I wrote a software renderer by JAVA in vscode.<br>
![image](pic1.png)<br>
The general process of the pipeline of this renderer is as follows:<br>
Read the model, obtain information ->put it into vertex buffer ->perform MV transformation on all vertices 
->extract 3 vertices according to the index to form a triangle ->remove triangles completely on the back of the camera 
->projection transformation ->record vertex depth ->homogeneous space clipping ->homogeneous division ->screen mapping<br>
->rasterization and interpolation -> shading. <br>
The main visual effects achieved by this renderer include perspective corrected UV texture mapping and a simple diffuse lighting model.<br>
## Tiny Online Greedy-Snake Game
**Solo**<br>
**Language: C++**<br>
**Time cost: 1 month**<br>
![image](snake.png)<br>
I wrote a tiny online game for at most two players using C++, running in Ubuntu<br>
This is a simple C++ console game, using deque for snakes and two-dimensional array for environment  <br>
I used frame synchronization, which means that both players must receive each other's actions before continuing to run the next frame <br>


