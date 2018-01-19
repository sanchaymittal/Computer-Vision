```import cv2
import numpy as np
import matplotlib.pyplot as pyplot

#IMREAD_COLOR = 1
#IMREAD_GRAYSCALE = 0
#IMREAD_UNCHANGED = -1


img= cv2.imread('testcase.jpg',0)


cv2.imshow('image', img)
cv2.waitkey(0)
cv2.destroyAllWindows()
```
