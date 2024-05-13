## Classify land use using Landsat satellite images
Context: 

    The main aim of this project is to classify land-use with the help of machine learning. 

Datasets: 

    In the project, there are four categories of images which are residential, forest, river and freeway. All other categories will be classified to others. The original size of the images is 256*256 pixels. Originally there are 500 images per class. But they have been divided to three datasets which called train, test and validation. There are 350 images per class in train dataset, 50 images in test dataset and 100 images in validation dataset. 

    Originally there are 21 classes but this project has selected only 4 classes. 
    
Document description:

    image_classification2.ipynb contains CNN model which is builded by myself and saved the model inte file CNN_model.keras.
    image_classification3.ipynb has downloaded a pre-trained model which is called VGG16. Then I convert the original VGG16 model into a sequential model. Add all layers except the first input layer and last output layer from VGG16 model into the new sequential model.
    image_classification4_ReloadModel.ipynb has tried to reload the saved CNN_model which is built in image_classification2.ipynb.Then evaluate and predict the test images with the reload model. 
    

Acknowledgements:

    Datasets is a part of the previous work of Yi Yang and Shawn Newsam, "Big-Of-Visual-Words and Spatial Extensions for Land-Use Classification", ACM sigspatial international conference on advances in geographic information systems (ACM GIS), 2010. 

OBS! Training images has not been uploaded here because of large size. All information about images found in path_list.scv
