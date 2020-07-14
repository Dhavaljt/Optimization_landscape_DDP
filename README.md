# Optimization_landscape_DDP
A brief description of the set of files and the experiments they stand for:  

1. Robustness_DL_Layers: Implementation of the fully connected layer network from the paper 'Are all layers created equal?'    
The remaining files have a similar structure with the following flow:  
a. Model definition   
b. Training and Testing  
c. Weight vectorization  
d. Experiments involving projections first for A, A+I, I and Irev projection matrices respectively  

To further understand each code segment, look at the file cifarCNN first.   
Name descriptions for the remaning files for reference:  
2. CIFARCNN - CNN architecture on CIFAR   
3. MNISTCNN - CNN architecture on MNIST  
4. CIFAR192 - Fully connected network of 192 nodes and 3 layers on CIFAR  
5. MNIST192 - Fully connected network of 192 nodes and 3 layers on MNIST  
6. CIFAR128 - Fully connected network of 128 nodes and 3 layers on CIFAR  
7. 128MNIST - Fully connected network of 128 nodes and 3 layers on MNIST  
8. resnetCIFAR - Resnet architecture on CIFAR  
9. resnetMNIST - Resnet architecture on MNIST  










