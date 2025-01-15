# Facial-Emotion-Recognition-using-ResNet
The goal of this project is to build a deep learning system that identifies and classifies facial emotions from grayscale images into seven predefined categories. This project leverages transfer learning with a pre-trained ResNet model to achieve accurate and efficient emotion recognition.
The model classifies facial expressions into the following categories:

0. Angry
1. Disgust
2. Fear
3. Happy
4. Sad
5. Surprise
6. Neutral

**Dataset Used:** [Facial Expression Dataset Image Folders FER2013](https://www.kaggle.com/astraszab/facial-expression-dataset-image-folders-fer2013)

![image](https://github.com/user-attachments/assets/69c5ac9f-8c11-4ec3-b820-e220cfa968ce)


### Model Architecture:

**ResNet:** A pre-trained ResNet (e.g., ResNet50) model is fine-tuned for emotion recognition.

**Modifications:** The final fully connected layer is replaced with one suited for the 7-class classification task.


### Result

* The model achieves stable convergence with competitive training and validation accuracies.
* Visualization plots illustrate the reduction in loss and improvement in accuracy over epochs.

![image](https://github.com/user-attachments/assets/9bb275b7-dba6-48d5-a3f5-606c11816372)

* The probability meter demonstrates the model's confidence for each emotion in a user-friendly manner.
* Accurate classification is observed across most categories.
