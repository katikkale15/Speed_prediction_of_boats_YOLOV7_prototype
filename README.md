# Speed_prediction_of_boats_YOLOV7
This notebook uses yolo v7 and modified DeepSORT algorithm to predict the speed of boats/ships and object tracking.

The code in the `deep_sort_code_speed_inclusive.py` is modeified for the speed detection. It can also be implemented for various other objects like cars, humans, cycle, aero-planes, etc.

The distance calculation used for speed was simply the distance between 2 points give by: $\sqrt{(x2-x1)^2+(y2-y1)^2$}

The model uses YOLO v7 which is really optimised, it can also be made with YOLO v8 and YOLO-NAS. It wouldnt make that much of a difference since the improvement is in terms of detecting tiny objects, and speed ofcourse. Our application being ships, personally do not think that would create a problem.
