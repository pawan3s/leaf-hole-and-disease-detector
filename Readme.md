leaf-hole-and-disease-detector is a simple algorithm for detecting leaf holes which corresponds to the disease named Septoria. It is done using the OpenCv method called Houghcircles. 
First the the Septoria affected leaf is uploaded. 


Then the image is converted into Binary image as we will use erosion to errode away the boundaries of foreground holes.In order to process the edges and remove noise we use the medianblur method.

Then using the Houghcircles we detetct the circles in the leaf and then draw circles over it as in the figure below.

