# Rice-leaf-disease-classification
In this project, we have chosen to use transfer learning – Mobilenet, Inception V3, Renet50, fastai deep learning library to classify images of rice leaf disease dataset having 3 different classes of disease with 40 images in each class.
	
  Main folder - Rice leaf disease 
	
  Sub folder – Bacterial leaf blight with 40 images
			     Leaf smut with 39 images
			     Brown spot with 40 images

i.	Downloading image data:
The data used for this project is imported from the local drive using os.listdir(), splitfolder ()  functions. 

ii.	Data Preparation:
Created dataframes for each subfolder.
Splitted into train and validation datasets.
Created a single directory ‘image_dir’.
Data augmentation is done and created train_generator,test_generator and val_generators.

iii.	 Modelling:
i.	Mobilenet
ii.	Resnet50
iii.	InceptionV3
iv.	Fastai

Model	Accuracy
Mobilenet	89.4231%
Resnet50	99.75%
InceptionV3	96.85%
Fastai	94.73%
