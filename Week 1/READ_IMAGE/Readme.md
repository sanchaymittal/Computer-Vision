## Read an Image

## imread()

Simple image read function of openCV
* Syntax : ``` cv.imread("image.jpg",detail )```
### detail 

* ```cv2.IMREAD_COLOR``` (1) : Loads a color image. Any transparency of image will be neglected. It is the default flag.
* ```cv2.IMREAD_GRAYSCALE``` (0) : Loads image in grayscale mode
* ```cv2.IMREAD_UNCHANGED``` (-1) : Loads image as such including alpha channel
  
Example:
```img = imread("image.jpg",0)``` OR ```img = imread("image.jpg", cv.IMREAD_GRAYSCALE)```

## imshow

Use the function cv2.imshow() to display an image in a window. The window automatically fits to the image size.

* Syntax : ```imshow("Window_name", imagevariable)```
* Example : ``` imshow("image", img) ```

## waitkey

cv2.waitKey() is a keyboard binding function. Its argument is the time in milliseconds. The function waits for specified milliseconds for any keyboard event. If you press any key in that time, the program continues. If 0 is passed, it waits indefinitely for a key stroke. It can also be set to detect specific key strokes like, if key a is pressed etc which we will discuss below.

## destroyAllWindows

cv2.destroyAllWindows() simply destroys all the windows we created. If you want to destroy any specific window, use the function cv2.destroyWindow() where you pass the exact window name as the argument.

### For Any other query.................[click here](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_image_display/py_image_display.html#display-image)


