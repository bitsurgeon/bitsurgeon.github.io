### **[Finding Lane Lines](https://github.com/bitsurgeon/CarND_LaneLines)**  

An image processing pipeline using OpenCV has been created to find the lane lines on the road from dashboard camera recordings.  

The following key components are included:  
* Gaussian blur
* Canny Edge Detector
* Region-of-interest selection
* Hough Transform
* Line filtering/averaging/extrapolation  

An example camera image is shown in below, as well as the processed image with lane markings on it.  
<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_LaneLines/master/writeup_images_output/extrapolate/0_camera_image.jpg" alt="Camera" width="200">
<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_LaneLines/master/writeup_images_output/extrapolate/6_lane_marked_image.jpg" alt="Marked" width="200">  

You can also view an example video output in below. As shown in the clip, the lanes are marked correctly for most of the time.  
[![Watch the video](https://img.youtube.com/vi/C0XeoygmMa8/mqdefault.jpg)](https://youtu.be/C0XeoygmMa8)  

For details, please follow this [link](https://github.com/bitsurgeon/CarND_LaneLines).  
