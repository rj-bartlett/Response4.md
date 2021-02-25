### Informal Response 4

#### [Image 1](https://github.com/rj-bartlett/Response4.md/issues/2#issue-816826639)
Filter 1: [[-1, 0, 1], [-2, 0, 2], [-1, 0, 1]]

Explanation: This filter makes the vertical lines in the original image more distinct. 

#### [Image 2](https://github.com/rj-bartlett/Response4.md/issues/3#issue-816827176)
Filter 2: [[-1, -2, -1], [0, 0, 0], [1, 2, 1]]

Explanation: This filter makes the horizontal lines in the original image more distinct.

#### [Image 3](https://github.com/rj-bartlett/Response4.md/issues/1#issue-816824854)
Filter 3: [[0, 1, 0], [1, -4, 1], [0, 1, 0]]

Explanation: This filter makes the diagonal lines in the original image more distinct. 

##### What are you functionally accomplishing as you apply the filter to your original array?
The filter has different weights that are multiplied to the values in each 3x3 array in the original array. The sum of these multiplied values creates a new array called a feature map that is a new, smaller image with a specific feature that is sharper compared to the original image. For example, the presence of horizontal or vertical lines can be extentuated by using a filter. 

##### Why is the application of a convolving filter to an image useful for computer vision?
The application of a convolving filter to an image is useful for computer vision because it extracts specific features that assists machine learning models in identifying the object(s) in a particular image. 

##### In effect what have you accomplished by applying this 2x2 pooling filter?
By applying the 2x2 pooling filter, dimensionality is reduced and the resolution of the image is increased. The largest value in each 2x2 matrix of the convoluted feature map is selected and displayed in the output, where the other 3 values in each 2x2 matrix are dropped.  

##### Does there seem to be a logic (i.e. maximizing, averaging or minimizing values?) associated with the pooling filter provided in the example exercise (convolutions & pooling)?
In the exercise it appears that there is a maximizing of values because only the largest value in a given 2x2 matrix is selected for the output. 

##### Did the resulting image increase in size or decrease? Why would this method be useful?
The resulting image decreased to 1/4 the original size. This is helpful if there are multiple convolutions happening to a single image. 

##### Convolve the 3x3 filter over the 9x9 matrix and provide the resulting matrix.
[Link to matrices](https://github.com/tyler-frazier/applied_machine_learning/blob/master/dailies/cnn_xtra_q.png)

Output: A 7x7 matrix
[0 0 0 3 0 0 0
 0 0 0 3 0 0 0
 0 0 0 3 0 0 0
 1 1 1 3 1 1 1
 0 0 0 3 0 0 0
 0 0 0 3 0 0 0
 0 0 0 3 0 0 0]
