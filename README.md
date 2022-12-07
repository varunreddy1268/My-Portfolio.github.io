
# Yolov4 Model Execution Steps:


1. For yolov4, since in the previous home work the envirnment got setup by using the environment.yml file.

1.1 past the recorder video in the yolov4 directory

1.2 Download and paste the yolov4 weights in yolo4 directory

2. change the directory to tensorlfow.yolov4 directory and run the detect_video.py file using the weights and input video  

Command:

>> python3 detect_video.py --weights path_of_weights --size 416 --model yolo4 path_of_yolo4 --video path_of_video 

3. Use cv2.write_ouptut() function and save the video or else screen record the video with name stamp and save the video.



# Yoloact Model Execution Steps:

1. Clone the yoloact repository 

2. set up the environment by running the environment set up yml file.

3. Download the coco data set.

4. Downlaod the pretrained weigths of the yoloact model and paste it in the yoloact directory 

5. Now run the detect_video.py file using the weights of the yoloact model and the path of the video file. 

6. record the the portion of screen where the predicted boxes are displaying in the video with your name stamp in it. 
