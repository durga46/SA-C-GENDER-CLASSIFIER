# SA-C-GENDER-CLASSIFIER
# Algorithm
1.Install deepface

2.Import necessary packages

3.Read the image

4.Analyze the gender using deepface


## Program:
```
/*
Program to implement 
Developed by   :DurgaDevi P
RegisterNumber :  212220230015
*/
```
```python
#install deepface
pip install deepface

#import packages
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

#read the image
img=cv2.imread('durga2.jpeg')
plt.imshow(img[:,:,::-1])
plt.show()

#Analyze gender
result=DeepFace.analyze(img,actions=['gender'])
result2=DeepFace.analyze(img,actions=['emotion'])

#print the gender
print("Gender : ",result['gender'])

```

## OUTPUT:
1. CODE :

![v2](https://user-images.githubusercontent.com/75235704/173245489-bc48c34a-9a75-466d-894e-f3ac5d759c31.PNG)



2. DEMO VIDEO YOUTUBE LINK:


https://youtu.be/yFzrwsKESZg
