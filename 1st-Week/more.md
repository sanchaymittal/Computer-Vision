# More...........
 
### namedWindows()

There is a special case where you can already create a window and load image to it later.
In that case, you can specify whether window is resizable or not.
It is done with the function ```cv2.namedWindow()```. By default, the flag is ```cv2.WINDOW_AUTOSIZE```.
But if you specify flag to be ```cv2.WINDOW_NORMAL```, you can resize window.
It will be helpful when image is too large in dimension and adding track bar to windows.
