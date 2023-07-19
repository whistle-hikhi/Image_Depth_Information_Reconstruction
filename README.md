# Image_Depth_Information_Reconstruction

The objective of this project is to calculate the depth of ojects in image using left and right image from camera by 3 methods:
- Pixel-wise matching
- Window-based matching
- Window-based matching with cosin similarity
<br />

1. Pixel-wise matching <br />

Input images left and right: <br />
<img src ="tsukuba/left.png">  <img src ="tsukuba/right.png"><br />
Output image: <br />
<img src="pixel_wise.png"> <br />

2. Window-based matching <br />

Input images: <br />
<img src ="tsukuba/left.png">  <img src ="tsukuba/right.png"> <br />
Output image: <br />
<img src ="window_based.png"> <br />

Input images: <br />
<img src ="Aloe/Aloe_left_1.png" width="250" height="250"> <img src ="Aloe/Aloe_right_2.png" width="250" height="250"> <br />
Ouput image: <br />
<img src ="window_based_false.png" width="250" height="250"> <br />

Limitation: can not handle with brightness images so we use window-based with cosin similarity <br />

3. Window-based matching with cosin similarity <br />

Input images: <br />
<img src ="Aloe/Aloe_left_1.png" width="250" height="250"> <img src ="Aloe/Aloe_right_2.png" width="250" height="250"> <br />
Ouput image: <br />
<img src ="window_based_cos_similarity.png" width="250" height="250"> <br />
