# Image Classification using a Convoultional Neural Network on the Flowers-102 Dataset 

## Project Overview
The project uses the Flowers102 dataset to train a deep convolutional neural network. The model architecture consists of several convolutional layers followed by fully connected layers. The training process includes data augmentation techniques such as random horizontal flip and random rotation to improve the generalization of the model.

### Prerequisites 

- Must use Python 3
- Google Colab(recommneded for training with GPU support)
- Google Drive(to save your model)

### Install Packages
!pip install torch torchvision(If on Google Colab it is preinstalled but could update)

## Running the code
On Google Colab click on Runtime then Run All and the code should excute, starting with training the model and then once trained it will save and then load the best model and test it in the evaultion loop, which reveals your final test classificstion accuracy.

### Tips
When Running code on Google Colab Make sure to change runtime to GPU, for faster execution.
