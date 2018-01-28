```
import cv2
import numpy as np
import matplotlib.pyplot as plt

#IMREAD_COLOR = 1
#IMREAD_GRAYSCALE = 0
#IMREAD_UNCHANGED = -1


img= cv2.imread('/home/sanchay/Desktop/k1PMuBQ7_400x400.jpg',1)



#cv2.imshow('image', img)
plt.imshow(img, cmap='gray', interpolation = 'bicubic')
#plt.plot([260,170],[270,170],'c',linewidth=5)  #remove this comment to see a line Across the pic
plt.show()
cv2.waitKey(0)
cv2.destroyAllWindows()
```
