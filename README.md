# Image features and homography<br/>
1. Given two images 'mountain1.jpg' and 'mountain2.jpg', extract SIFT features and draw the keypoints for both images. <br/>
2. Match the keypoints using k-nearest neighbour (k=2), i.e., for a keypoint in the left image, finding the best 2 matches in the right image. Filter good matches satisfy m.distance < 0.75 n.distance, where m is the first match and n is the second match. <br/>
3. Compute the homography matrix H (with RANSAC) from the first image to the second image.<br/>
4. Draw the match image for around 10 random matches using only inliers.<br/>
5. Warp the first image to the second image using H. The resulting image should contain all pixels in 'mountain1.jpg' and 'mountain2.jpg'. <br/>

Skills: Python,OpenCV
