# Image Classification with Neural Networks — FCN vs. CNN

_Intro to Artificial Intelligence — University of Tehran_

This project explores **image classification** using two neural network architectures:  
a **Fully Connected Neural Network (FCN)** and a **Convolutional Neural Network (CNN)**.  
The implementation is done in **PyTorch**, and results are compared on the **CIFAR-10 dataset**.


## Tasks

1. **Dataset Preparation**
   - Use the **CIFAR-10 dataset** (60,000 color images of size 32×32 across 10 classes).
   - Split into training, validation, and test sets.
   - Convert data into `DataLoader` format for efficient training and batching.
   - Visualize random samples from each class.

2. **Fully Connected Network (FCN)**
   - Flatten images into feature vectors.
   - Build a multi-layer FCN using PyTorch `nn.Module`.
   - Apply **Dropout** to reduce overfitting.
   - Train for 60 epochs using **Cross-Entropy Loss** and **Adam optimizer**.
   - Record training/validation loss and accuracy, and plot curves.

3. **Convolutional Neural Network (CNN)**
   - Design and implement a CNN with convolution, pooling, and fully connected layers.
   - Keep total trainable parameters comparable to the FCN (~500k ± 33.5M).
   - Train under the same conditions as FCN (60 epochs).
   - Evaluate on the test set and compare performance with FCN.
   - Visualize 24 misclassified images with true vs. predicted labels.

4. **Feature Space & Visualization**
   - Extract intermediate feature representations from CNN.
   - Use **k-Nearest Neighbors (kNN)** to explore similarity in feature space.
   - Apply **t-SNE** for dimensionality reduction and visualize clustering patterns.
   - Visualize **feature maps** from convolutional layers to interpret learned features.

5. **Evaluation**
   - Compare FCN and CNN in terms of:
     - Training/validation curves
     - Test accuracy
     - Overfitting behavior
     - Interpretability of feature maps and embeddings


## License

This project is licensed under the **MIT License**.


## Acknowledgements

Developed under the supervision of **Dr. Fadaei** and **Dr. Yaghoubzadeh**  
Designed by **Mehdi Jamalkhah, Mohammadamin Yousefi, Amin Aghakasiri**

