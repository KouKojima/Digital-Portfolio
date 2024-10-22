# Digital-Portfolio
I wrote a software renderer by JAVA in vscode <br>
The general process of the pipeline of this renderer is as follows:
Read the model, obtain information ->put it into vertex buffer ->perform MV transformation on all vertices ->extract 3 vertices according to the index to form a triangle ->remove the back and some very coarse-grained deletions ->projection transformation ->record vertex depth ->homogeneous space clipping ->homogeneous division ->screen mapping ->rasterize interpolation coloring. In the initial stage of building this pipeline, we can ignore the vertex buffering step because it is an optimization operation and we can implement the function first.
