# Digital-Portfolio
## Software Renderer
I wrote a software renderer by JAVA in vscode.<br>
![image](pic1.png)<br>
The general process of the pipeline of this renderer is as follows:<br>
Read the model, obtain information ->put it into vertex buffer ->perform MV transformation on all vertices <br>
->extract 3 vertices according to the index to form a triangle ->remove triangles completely on the back of the camera <br>
->projection transformation ->record vertex depth ->homogeneous space clipping ->homogeneous division ->screen mapping<br>
->rasterization and interpolation -> shading. <br>
The main visual effects achieved by this renderer include perspective corrected UV texture mapping and a simple diffuse lighting model.<br>
## Tiny Online Greedy-Snake Game
I wrote a tiny online game for at most two players using C++, running in Ubuntu<br>

