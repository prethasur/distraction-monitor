# distraction-monitor

*Training-YOLOv5-On-Custom-Data*

In this project we make real-time distraction detection, that can be used with webcams, monitoring a person's focus on the laptop screen. this can we used on online meeting set-ups to keep a track on participants, specially during online classes that involve constant attention to the laptop screen without interacting to the background. Activities like talking to someone else - over phone or physically, consuming food, sleeping, looking away from screen along with facial expressions or handling something else like a rubiks cube detects one as distracted. On the other hand gazing at the screen with eyes open (fully/partially while typing) is considered focused.

Here we have used the yolov5 model from https://github.com/ultralytics/yolov5 ; its small version to be precise. We imported the weights from training the coco dataset, then trained the model further with images collected(from our webcam) and labeled using the labelImg app : https://github.com/tzutalin/labelImg

We collected 100 images - 50 each from focused and distracted classes.

We ran 100 epochs on a batch size of 16 imgs. the training was done on CPU and each epoch took about an hour to complete.


P.S: will perhaps create a crome extension for gmeet :)
