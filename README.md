# Image-Stitching
### Overview
In image stitching, I picked the correspondences between both images manually. Then I used these correspondences to compute the homography matrix by forming a linear system and compute its SVM. Then used inverse warping between the images to be able to linearly interpolate each pixel from the output image from the original image. I did this by splitting the image into three channels (RGB) and then computing the linear interpolation for each. At the very end, combined all three channels to give the final output.
### Results
 <img src="https://raw.githubusercontent.com/shamshegab/Image-Stitching/master/images/image_stitching_output.PNG" alt="drawing" width="480"/>
