# cats-vs-dogs-classification
**Image Classification with Deep Learning**
This project is designed to classify images into two categories: "cats" and "dogs" using deep learning techniques. The code uses Python and several libraries, including NumPy, Matplotlib, OS, Pandas, Seaborn, and Random.

**Table of Contents**
Introduction
Installation
Usage
Models
Training
Results
Contributing
License

**Introduction**
In this project, we build an image classification system that can distinguish between images of cats and dogs based on their file paths. We use deep neural networks with ReLU activation functions to achieve this task.

**Installation**
Before running the code, make sure you have the required libraries installed. You can install them using pip:

pip install numpy matplotlib pandas seaborn

**Usage**
To use this code for image classification, follow these steps:

1.Clone the repository to your local machine:
git clone https://github.com/your-username/image-classification.git

2.Navigate to the project directory:
cd image-classification

3.Run the image classification script:
python image_classification.py

**Models**
We have implemented three different neural network models for image classification. These models can be found in the models.py file. You can choose the model you want to use by modifying the code in the image_classification.py file.

**Training**
We experimented with different numbers of epochs (50, 70, and 100) to train our models. After analyzing the loss plots, we found that 50 epochs yielded the best results with the lowest loss.

To train the models, adjust the number of epochs in the image_classification.py file and run the script as mentioned in the Usage section.

**Results**
The results of the image classification are displayed in the form of loss plots and accuracy metrics. You can find these plots in the "results" directory. The results "/loss_plots.png" file shows the loss curves for each model, and the "results/accuracy_metrics.txt" file contains accuracy metrics for different epochs.

**Contributing**
We welcome contributions to this project. If you have any suggestions or want to report issues, please create a new issue on the GitHub repository.

**License**
This project is licensed under the MIT License - see the LICENSE file for details.
