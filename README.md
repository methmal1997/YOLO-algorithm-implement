# YOLO-algorithm-implement



Here i couldn't able to add weight file
So you can download from below link

https://pjreddie.com/media/files/yolov3.weights

After that put it in the this ' YOLO algoritham\YOLOv3_TF2\weights' ,weight folder 

Next step is 'python convert_weights.py' in terminal and run this command
Then it will create nothr 3 files in above mentioned weight file and aftr that
YOLO algoritham\YOLOv3_TF2\data\images directory put some images that you want to detect 
Then run the 'python image.py' in terminal

If you want to feed from the camera run 'python video.py' in terminal
But if you want add video except to it change 

 cap = cv2.VideoCapture(0) to  cap = cv2.VideoCapture(videopath)
