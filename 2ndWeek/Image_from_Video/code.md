```
import cv2
import numpy as ny

v = cv2.VideoCapture(0)

while(True):
    ret, fr = v.read()


    cv2.imshow("video",fr)
    if cv2.waitKey(1)==ord('s'):
        cv2.imwrite("fromVideo.png",fr)
        break

cv2.destroyAllWindows
```
