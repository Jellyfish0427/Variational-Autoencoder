## Introduction
Implement variational autoencoder trained on the eye dataset using PyTorch.

## Model architecture
![image](https://user-images.githubusercontent.com/128220508/226120577-101d9171-b4bf-427e-b4ae-c9efe1d52a16.png)

## Dataset
There are two classes in the dataset, containing female eyes (0) and male eyes (1).
The total number of data is 1476 and the shape of each image is (50,50,3).
Example:  
![226117181-b6881e55-f36a-40ae-aa99-f2b31913bad7](https://user-images.githubusercontent.com/128220508/226120674-4547753f-942d-4cc2-b42f-b12909aa237c.png)  

## Implementation
VAE.py  
1. Train VAE model  
2. Print original image and generate image  
3. Print the generated images of [3, 227, 841, 1475]  
4. Model weight: VAE.pth  
5. Generate gen_data.npy, gen_label.npy  

Detail is in the report folder.
