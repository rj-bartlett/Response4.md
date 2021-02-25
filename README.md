### Informal Response 4

Filter 1: [[-1, 0, 1], [-2, 0, 2], [-1, 0, 1]]
[Image 1]()
Explanation: This filter makes the vertical lines in the original image more distinct. 

Filter 2: [[-1, -2, -1], [0, 0, 0], [1, 2, 1]]
[Image 2](https://github.com/rj-bartlett/Response4.md/issues/3#issue-816827176)
Explanation: This filter makes the horizontal lines in the original image more distinct.

Filter 3: [[0, 1, 0], [1, -4, 1], [0, 1, 0]]
[Image 3](https://github.com/rj-bartlett/Response4.md/issues/1#issue-816824854)
Explanation: This filter makes the diagonal lines in the original image more distinct. 

##### What are you functionally accomplishing as you apply the filter to your original array?

##### Why is the application of a convolving filter to an image useful for computer vision?

##### In effect what have you accomplished by applying this 2x2 pooling filter?

##### Does there seem to be a logic (i.e. maximizing, averaging or minimizing values?) associated with the pooling filter provided in the example exercise (convolutions & pooling)?

##### Did the resulting image increase in size or decrease? Why would this method be useful?

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
