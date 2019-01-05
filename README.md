# pytorch-challenge
Using a pretrained model vgg16 and inception_v3 to train a model to idenitfy 102 species of flower
## Trained model with flower dataset
To get the trained model run this in the notebook
- vgg16 with a learning rate of 0.0001
````bash
!pip install gdown==3.6.0
my_file_id = '1bibKeN9mRXk2X_fE382kxfTr13ifUJ2j'
!gdown https://drive.google.com/uc?id={my_file_id}
````
- inception with a learning rate of 0.01
````bash
!pip install gdown==3.6.0
my_file_id = '1KftzAlpXubB7ybQCtzqqhtAUhAgyjpS8'
!gdown https://drive.google.com/uc?id={my_file_id}
````
