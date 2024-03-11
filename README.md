# Fall-Detection-using-YOLOv7-Human-Pose-Estimation

Description:
This GitHub repository contains a Python script for detecting falls in a video using the YOLOv7 model for human pose estimation. The experiment utilizes the YOLOv7 repository by WongKinYiu, focusing on pose estimation to identify potential falls based on changes in shoulder and foot heights. The script processes a video, annotates detected falls, and sends notifications via Telegram. Key components include YOLOv7 model loading, video processing, fall detection logic, and Telegram integration.

How to Use:

Clone the YOLOv7 repository and install dependencies.
Load the YOLOv7 model from the pre-trained checkpoint.
Specify the input video file path (video.mp4).
Run the script to process the video and detect falls.
View the output video with fall annotations (<video_name>_keypoint.mp4).
Receive Telegram notifications for detected falls.

Ensure proper setup of the YOLOv7 repository and model weights.
Adjust the threshold for fall detection as needed.
Update the Telegram token and receiver ID for notifications.
https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7-w6-person.pt- download yolov7-w6-person.pt from here.
