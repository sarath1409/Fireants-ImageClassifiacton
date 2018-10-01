# Fireants-ImageClassification
- Multi Class Classification Model using Deep Learning Techniques.
- We use VGG16 Pre-Trained Model.

## Packages Used
- Numpy
- Skimage
- Keras

## Dataset Description
- The datset contains images of ants. 
- The dataset can be broadly divided into ants and fireants. 
- Fireant's sting may be fatal. So, to identify ants whether they are normal ants or fireants is required.
The given dataset contains 3 folders:
  - Ari
  - Azumaoozuari
  - Hiari
  
- Ari folder has images of normal ants.
- Azumaoozuari and Hiari folders has images of fireants.
- __In each folder we will again have Ari, Azumaoozuari, Hiari.


## Notebook 1
- FireAnt_Notebook1.ipynb is used to augment images based on different parameters specified in ImageDataGenerator. 
- The same notebook will create a new folder named "output-folder" one level above the current directory in which there are 3 folders:
  - test
  - train
  - validation
  
```text

Training_percentage = 0.6
Validation_percentage = 0.2
```

### Notebook 2
- Notebook 2 is used to train a model on the given images and predict on new images.
- However more optimization to model and hyper parameter tuning is required to achieve good Accuracy.
