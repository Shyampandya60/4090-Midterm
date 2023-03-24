# 4090-Midterm
Trained a binary classifier (called A) on the dataset using transfer learning (exactly like Assignment 1). The images should be downscaled to 128x128
Next, trained the SRGAN to generate 128x128 images. Each image of the training is downscaled to 32x32.
Showed some examples of scaled images in JNB
Utilized the images generated by SRGAN in order to train a new model (called B)
Trained the SRGAN for at least 150 epochs
Divided the dataset into 70% training and 30% testing
Applied normalization and image transformation, and demonstrate some of the transformed samples
Compared the performance of both models using different metrics such as F1, Accuracy, AUC
