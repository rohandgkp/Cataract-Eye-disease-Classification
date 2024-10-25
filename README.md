# Cataract-Eye-disease-Classification
The experiment was conducted on a dataset (4217 images) consisting of 4 classes, namely glaucoma (1007 images), normal (1074 images), diabetic retinopathy (10980 images), and cataract (1038 images).
The images were resized into (180, 180).
The dataset was split in 80:20 for training (3374 images) and testing (843 images).
A custom CNN model was built with 3 convolutional layers of 16, 32, and 64 neurons each and trained over 10 epochs.
Data augmentation was performed - RandomFlip, RandomrRotation, and RandomZoom.
A dropout layer with 0.2 dropout rate was added and then trained on 50 epochs.
The custom CNN model achieved a testing accuracy of 86.36%.
