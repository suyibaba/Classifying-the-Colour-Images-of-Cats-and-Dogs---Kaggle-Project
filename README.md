# Classifying-the-Colour-Images-of-Cats-and-Dogs---Kaggle-Project





                ##DETAILS 
                
                Binary Classification Problem
                Colored Images
                No standard Dimension
                Kaggle Dataset


PROCESS


1. CNN with small dataset (4 convolutional layers)
2. CNN with data augmentation to improve performance due to the small dataset
3. Transfer Learning



      DATA PREPROCESSING 
          Read the picture files
          Decode the JPEG content to RGB grids of pixels
          Convert these into floating point tensors
          Rescale the pixels values (between 0 and 255) to the (0,1) interval
          

![image](https://user-images.githubusercontent.com/64482231/197638114-2cb7161f-38ce-42da-878e-d98d8b0afe32.png)


The graph suggest there is an overfitting in the model. With each Epoch as Accuracy is increasing , the validation accuracy is not increasing proportionally. 

To fix the overfitting, some dummy data was created. Existing data are modified into different forms by applying zoom,shear


DATA AUGMENTATION PREPROCESSING: 


