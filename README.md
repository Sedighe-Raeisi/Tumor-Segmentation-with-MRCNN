# Tumor-Segmentation-with-MRCNN
# Downlading the Dataset:  
In this project I downloaded the data from the link: 
[https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
# Annotating the images:  
Then I used [VGG-Annotator](https://www.robots.ox.ac.uk/~vgg/software/via/), and annotate the tumors in images. 
# Training the Model:
Then I used [the Mask-RCNN](https://github.com/matterport/Mask_RCNN)
At first, I cloned the repository.
I made a class for configuration and a custom dataset. I introduced the object: Tumor.
I trained the pre-trained model for my dataset. I saved the weights of this trained model. 
Finally, I used these weights for detecting the position of the tumor on some MRI images:   
![image](https://user-images.githubusercontent.com/67642255/154487431-a741d53d-5ea4-4ac0-93fe-fdca2ebb5fa4.png)

Considering the disconnection of collab during training, I couldn't train my model for more epochs.
