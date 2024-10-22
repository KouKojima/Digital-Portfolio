# Digital-Portfolio
I wrote a software renderer by JAVA in vscode.<br>
![image](pic1.png)<br>
The general process of the pipeline of this renderer is as follows:<br>
Read the model, obtain information ->put it into vertex buffer ->perform MV transformation on all vertices <br>
->extract 3 vertices according to the index to form a triangle ->remove the back and some very coarse-grained deletions <br>
->projection transformation ->record vertex depth ->homogeneous space clipping ->homogeneous division ->screen mapping<br>
->rasterize interpolation coloring. <br>
