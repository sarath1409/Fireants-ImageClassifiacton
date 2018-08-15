## Fireants-ImageClassification
The datset contains images of ants. The dataset can be broadly divided into ants and fireants. Fireant's sting may be fatal. So, to identify ants whether they are normal ants or fireants is required.
The given dataset contains 3 folders:
  1.Ari
  2.Azumaoozuari
  3.Hiari 
Ari folder has images of normal ants.
Azumaoozuari and Hiari folders has images of fireants.

### Notebook 1
FireAnt_Notebook1.ipynb is used to augment images based on different parameters specified in ImageDataGenerator. 
The same notebook will create a new folder named "output-folder" one level above the current directory in which there are 3 folders:
  1.test
  2.train
  3.validation
training_percentage, validation_percentage is set to 0.6,0.2 respectively.
In each folder we will again have Ari, Azumaoozuari, Hiari again.

### Notebook 2
FireAnt_Notebook2.ipynb is used to train a model on the given images and predict on new images.
For feature extraction and fine-tuning we've used a pre-trained convnet VGG16.
