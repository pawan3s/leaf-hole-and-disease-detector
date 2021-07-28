leaf-hole-and-disease-detector is a simple algorithm for detecting leaf holes which corresponds to the disease named Septoria. It is done using the OpenCv method called Houghcircles. 
First the the Septoria affected leaf is uploaded. 

![Soyabin](https://user-images.githubusercontent.com/61246422/127370933-9c74069e-ffbe-483c-aa3c-dc5d4e01bb77.jpg)


Then the image is converted into Binary image as we will use erosion to errode away the boundaries of foreground holes.In order to process the edges and remove noise we use the medianblur method.

Then using the Houghcircles we detetct the circles in the leaf and then draw circles over it as in the figure below.

![Capture](https://user-images.githubusercontent.com/61246422/127370899-ad7d09f9-84b8-4976-90f1-76ecbeda1cce.JPG)
