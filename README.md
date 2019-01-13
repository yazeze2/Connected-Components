# Object Detection (Connected-Components)
Counting Connected Components in an Image

![image](https://user-images.githubusercontent.com/32316270/45660628-4097a500-babf-11e8-9bf3-21c7e71e9991.png)

Based on the pixel intensity distribution exhibited on the Histogram, the original image is segmented at Threshold T=10. The objects of interest is represented by the smaller peak while the larger peak represents the background. 
All pixels less than 10 (object of interest)  are assigned 1 while pixels greater than 10 are assigned 0. The resulting segmented image is presented below.

![image](https://user-images.githubusercontent.com/32316270/45660633-4c836700-babf-11e8-8894-156ed0b98965.png)

The algorithm identified 3 components as shown below

![image](https://user-images.githubusercontent.com/32316270/45660645-691f9f00-babf-11e8-8f0e-79077d010abb.png)
