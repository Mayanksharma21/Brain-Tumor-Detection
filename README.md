# Brain Tumor Detection using Convolutional Neural Networks (CNN)
This project uses deep learning to detect brain tumors in MRI images. The code is written in Python and uses Keras library for building the model.
## Dataset
The dataset used for this project is available at [Dataset](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection). It contains 2 folders, "yes" and "no" which contains MRI images of the brain. The "yes" folder contains MRI images which are brain tumor positive and the "no" folder contains MRI images which are brain tumor negative.
## Model Architecture
The model is a convolutional neural network (CNN) with three convolutional layers, each followed by a max pooling layer. The output of the third convolutional layer is flattened and fed to two fully connected layers with 64 and 1 neurons, respectively. The last layer uses sigmoid activation to produce a binary classification output.
## Training and Evaluation
The dataset is split into training and testing sets, and the training data is normalized. The model is trained using binary cross-entropy loss and Adam optimizer for 10 epochs with a batch size of 16. The accuracy of the model is evaluated using the testing set.
## Result
After training the model, it is saved in a '.h5' file format. During the testing phase, if the model outputs 1, it means a brain tumor is detected in the image; otherwise, if it outputs 0, no brain tumor is detected.
## Video
https://user-images.githubusercontent.com/86908473/235313357-7b3c6dde-4c49-4557-aef5-9abb52619145.mp4


