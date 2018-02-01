```
import cv2
import numpy as ny

img = cv2.imread('/home/sanchay/Desktop/k1PMuBQ7_400x400.jpg',-1)

cv2.imshow('imawesome',img)

k = cv2.waitKey(0)
if k == ord('s'):
    cv2.imwrite("i m hero.jpg",img)
    cv2.destroyAllWindows()
else:
    cv2.destroyAllWindows()
```
