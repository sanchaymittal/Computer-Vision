### Adding Text
```
import cv2
import numpy as ny
import matplotlib.pyplot as py

img = ny.zeros((512,512,3), ny.uint8) #For dark image

#cv2.rectangle(img,topleftCorner, bottomRightCorner, Color, Thickness)
img = cv2.line(img,(0,0),(255,255),(255,0,0),5)

#cv2.rectangle(img,topleftCorner, bottomRightCorner, Color, Thickness)
img = cv2.rectangle(img,(384,0),(510,128),(0,255,0),3)

#cv2.circle(img, centre, radius,color,thickness )
img = cv2.circle(img,(255,255),56,(0,0,255),cv2.LINE_AA)

#cv2.ellipse(img, center, axes, angle, startAngle, endAngle, color[, thickness[, lineType[, shift]]])
img = cv2.ellipse(img,(256,100),(100,50),10,0,180,(0,255,0),-1)

#cv2.putText(img,'text',Co-ordinates, FONT, Font_Size, Color, Thickness, Line_Type)
cv2.putText(img,'OpenCv',(20,350),cv2.FONT_HERSHEY_SIMPLEX,4,(255,255,255),2,cv2.LINE_AA)
#cv2.putText(img,'OpenCV',(10,500), font, 4,(255,255,255),2,cv2.LINE_AA)
#font = cv2.FONT_HERSHEY_SIMPLEX

cv2.imshow('img',img)
cv2.waitKey(0)
cv2.destroyAllWindows
```
