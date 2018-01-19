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

### For Any other query.................[click here](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_image_display/py_image_display.html#display-image)


