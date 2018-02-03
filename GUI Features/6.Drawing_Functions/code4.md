### OpenCV Logo Using Drawing Fuctions

```
import cv2
import numpy as ny
import matplotlib.pyplot as py

img = ny.zeros((512,512,3), ny.uint8) #For dark image


#cv2.ellipse(img, center, axes, angle, startAngle, endAngle, color[, thickness[, lineType[, shift]]])
img = cv2.ellipse(img,(205,255),(40,40),0,0,270,(0,255,0),12)
img = cv2.ellipse(img,(255,165),(40,40),135,0,270,(0,0,255),12)
img = cv2.ellipse(img,(305,255),(40,40),-45,0,270,(255,0,0),12)


#cv2.putText(img,'text',Co-ordinates, FONT, Font_Size, Color, Thickness, Line_Type)
cv2.putText(img,'OpenCv',(75,380),cv2.FONT_HERSHEY_SIMPLEX,3,(255,255,255),6,cv2.LINE_AA)
#font = cv2.FONT_HERSHEY_SIMPLEX
#cv2.putText(img,'OpenCV',(10,500), font, 4,(255,255,255),2,cv2.LINE_AA)


cv2.imshow('img',img)
cv2.waitKey(0)
cv2.destroyAllWindows
```
