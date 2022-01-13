# Steganography_Swaraaj
Steganography has been used for centuries, but these days, hackers and IT pros have digitized The word “steganography” seems fancy, but it actually comes from a fairly normal place. The root “steganos” is Greek for “hidden” or “covered,” and the root “graph” is Greek for “to write.” Put these words together, and you’ve got something close to “hidden writing,” or “secret writing.”
Read me 

Steganography: Hiding textinside another

To run the .ipynb
you need to install Jupyter notebook or can run the code in google collab

https://colab.research.google.com/?utm_source=scs-index

To run the code
you need to install 



1.    OpenCv

2.    Matplotlib

3.    Numpy







To install OpenCv
run   “pip install opencv-python”.



To install Matplotlib run   “pip install matplotlib”.



To install Numpy run   “pip install numpy”.

import cv2
from matplotlib import pyplot as plt
from math import log10, sqrt 
import numpy as np



Import these to
the program
STEPS: 



1.    
Import
all the requires modules



2.  Take input of the image



3.  img1
= cv2.imread("Cover_1.png")



4.  temp=
cv2.imread("Cover_1.png")
1.  Resize the image to standard size



 



img1=cv2.resize(img1,
(256,256))



temp=cv2.resize(temp,
(256,256))



row,col,dim=temp.shape



print(row,col,dim)



1.    
Choose
a key and message



2.  while(1):



3.   
  key=input("Enter the security key :
\n")



4.   
  if len(key)==0:



5.   
      print("Key size cannot be 0 ..
\nReEnter Key")



6.   
  else:



7.   
      break



8.  message=input("\nEnter
the message to be hidden : \n")



9.  key_indx=0



10.        
message_len=len(message)



                                                     



11.  Perform Encryption algorithm on the
image and key





 
