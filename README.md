# CONVERTING IMAGE TO PENCIL SKETCH

### A RGB image can be converted into a pencil sketch using 4 easy steps!

![img.jpg](attachment:img.jpg)

### Step 1: Get the image and convert it into grayscale by using COLOR_BGR2GRAY from cv2.
![img1.jpg](attachment:img1.jpg)

### Step 2: Invert the image i.e, obtain the negative of the grayscale image using bitwise_not from cv2.
![img2.jpg](attachment:img2.jpg)

### Step 3: Blur the image by applying Gaussian filter to the inverted image.
![img3.jpg](attachment:img3.jpg)

### Step 4: Merge the gray scale image and the Gaussian filter applied image.
![img4.jpg](attachment:img4.jpg)

### The sketch is ready!
