# EZ-cDCGAN_with-Mnist  
# Train  
run cdcgan.py then would output model generator.h5  
# evalua/test  
1. download generator.h5 has been trained by me or use your own trained model.  
2. run generator.py 
just change the array by 16 elements you like.  
ex:  condition=[1,2,3,4,5,6,7,8,9,5,4,3,2,1,0,8]  
depend on condition,generator creat the output image.  
![img](images/mnist1.png)
