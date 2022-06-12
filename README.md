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
![v1](https://user-images.githubusercontent.com/75235704/173245436-449d8936-edfb-491d-a5df-b23b3f8e2c63.PNG)


2. DEMO VIDEO YOUTUBE LINK:



