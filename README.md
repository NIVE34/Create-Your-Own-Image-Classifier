# Create-Your-Own-Repository
Training the Network (train.py):

Use a dataset of flower images (102 categories) organized in train, validate, and test folders.
Options: Choose model architecture (alexnet, densenet121, or vgg16), set learning rate, epochs, and enable GPU if available.
Prediction (predict.py):

After training, use this script to predict flower species from an image.
Options: Return top K predictions, use a .json file for category mapping.
GPU for Training:

Use CUDA (if you have an NVIDIA GPU), cloud services, or Google Colab (free GPUs) for training.
Hyperparameters:

More epochs improve training accuracy but can cause overfitting. A smaller learning rate leads to more precise training but takes longer.
DenseNet121 works well for images but takes longer to train.
Pre-Trained Model:

A pre-trained model (checkpoint.pth) can be used to make predictions without retraining.
