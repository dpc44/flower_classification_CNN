Below are the steps to follow in order to create the necessary environments to be able to run the code for the models 
attached alongside. 


step 1 : Download 102-flower Oxford dataset through this url :https://www.robots.ox.ac.uk/~vgg/data/flowers/102/

step 2 : create environment of conda with this requirements supplied in the requirements file ("project_flower.yml")
or create conda env through this file

step 3: 
1. In normal folder
i.) Extract the zip file dataset in the folder named full_images (the direction will be full_images\\image102)
ii.) Then run the file named create_folder to get the dataset of seperate 102 classes image
iii.) Finally, go to path ./normal-segment/normal and run the jupyter notebook files to run the different models.

2. Segment folder
i.) Extract the zip file dataset in the folder named full_images (the direction will be full_images\\image102)
ii.) Then run the file named seg_image, to get the full segmented images. 
iii.) After that run the folder named create_folder-seg_image to get the dataset of seperate 102 classes image
iv.) Finally, go to path ./normal-segment/segment and run the jupyter notebook files to run the different models.