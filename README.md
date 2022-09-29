# Cotton-Plant-Disease-Detection

➔ Determine cotton plant and leaf disease.                                          
➔ Identify fresh cotton leaf , diseased cotton leaf, fresh 
cotton tree and diseased cotton tree by image processing.                                               
➔ The problem was to predict and determine cotton 
plant disease.

### --------------------Algorithms I used:-----------------------
I used Convolutional Neural Networks (CNN).                                                   
Architecture: ResNet 50 ,VGG 16 and custom.

#### Custom Network: 
1.Convolutional Layer - 2                             
Max Pooling layer - 2                               
Flatten and Dense layer                             
Input size: 64*64                

2. Convolutional Layer - 4                   
Max Pooling layer - 3   
Flatten and Dense layer                         
Input size: 224*224          

### ----------------Result and Discussion------------------------
#### Architecture Accuracy:                       
 VGG16      96%              
 ResNet50  65%                               
 Custom    97%           

#### Validation Accuracy:
VGG16      96%              
 ResNet50  76%                               
 Custom    91%    
 
 #### Loss:
 VGG16      11%              
 ResNet50                                  
 Custom     7%    
 
Designed architecture shows highest accuracy 97% besides VGG16 shows 96%
Accuracy which is pretty good. On the other hand, ResNet50 has given lower 
accuracy may be the reason is small dataset.

![cotton plant1](https://user-images.githubusercontent.com/68694418/192964323-f4207fe5-e607-476b-998c-f8039e63842e.png)

Figure 1 shows that, train accuracy increased 
gradually.Test accuracy also increased gradually 
but the curve is not smooth. 



![cotton plant](https://user-images.githubusercontent.com/68694418/192965048-984bb276-44ca-4daa-b8c9-a0d3a7ecfc84.png)

Figure 2 shows that, train loss decreased 
gradually. Test loss also decreased gradually 
but the curve is not smooth.
