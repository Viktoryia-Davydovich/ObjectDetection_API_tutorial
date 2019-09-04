annotations: This folder is used to store all _.csv files and the respective TensorFlow _.record files, which contain the list of annotations for our dataset images.

images: This folder contains a copy of all the images in our dataset, as well as the respective \*.xml files produced for each one, once labelImg is used to annotate objects.

images\train: This folder contains a copy of all images, and the respective \*.xml files, which will be used to train our model.

images\test: This folder contains a copy of all images, and the respective \*.xml files, which will be used to test our model.

pre-trained-model: This folder contains the pre-trained model of our choice, which shall be used as a starting checkpoint for our training job.

training: This folder contains the training pipeline configuration file _.config, as well as a _.pbtxt label map file and all files generated during the training of our model.
