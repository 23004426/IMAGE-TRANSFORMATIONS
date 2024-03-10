# IMAGE-TRANSFORMATIONS


## Aim
To perform image transformation such as Translation, Scaling, Shearing, Reflection, Rotation and Cropping using OpenCV and Python.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:


### Step2:


### Step3:


### Step4:


### Step5:


## Program:
```python
Developed By:
Register Number:
i)Image Translation
```python
import numpy as np
import cv2
import matplotlib.pyplot as plt
image = cv2.imread("flower.jpg")
image = cv2.cvtColor(image,cv2.COLOR_BGR2RGB)
plt.axis('off')
plt.imshow(image)
plt.show()

```

ii) Image Scaling
```python
import numpy as np
import cv2
import matplotlib.pyplot as plt
image = cv2.imread("flower.jpg")
image = cv2.cvtColor(image,cv2.COLOR_BGR2RGB)
plt.axis('off')
rows,cols,dim = image.shape
M = np.float32([[1,0,114],[0,1,-230],[0,0,1]])
translated_image = cv2.warpPerspective(image,M,(cols,rows))
plt.axis('off')
plt.imshow(translated_image)
plt.show()

```



iii)Image shearing
```python

```



iv)Image Reflection
```python

```




v)Image Rotation
```python

```




vi)Image Cropping
```python

```





```
## Output:
### i)Image Translation
![image](https://github.com/23004426/IMAGE-TRANSFORMATIONS/assets/144979327/f814286c-f020-44ab-95a5-86b802983350)

### ii) Image Scaling
![Uploading image.png…]()


### iii)Image shearing


### iv)Image Reflection


### v)Image Rotation


### vi)Image Cropping




## Result: 

Thus the different image transformations such as Translation, Scaling, Shearing, Reflection, Rotation and Cropping are done using OpenCV and python programming.
