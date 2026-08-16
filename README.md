# Transfer Learning and Hugging Face Image Classification
PART A: Dataset Preparation

In this part, an image dataset was downloaded from Kaggle and prepared for the transfer learning experiment. The images were loaded and preprocessed by resizing them to the required input size and normalizing the pixel values. The dataset was divided into three subsets: training, validation, and testing sets. The training set was used to train the model, the validation set was used to monitor model performance during training, and the testing set was used to evaluate the final performance of the model.

PART B: Implementing Transfer Learning

In this part, a pre-trained deep learning model such as **ResNet-50** was loaded and used for transfer learning. The original final classification layer was replaced with a new classification layer according to the number of classes in the selected dataset. The feature extraction layers of the pre-trained model were frozen so that the already learned features were preserved. The modified model was then compiled using an appropriate optimizer, loss function, and evaluation metric.

PART C: Model Training and Performance Evaluation

The transfer learning model was trained using the prepared training dataset and validated using the validation dataset. During training, **training accuracy, validation accuracy, training loss, and validation loss** were recorded for every epoch. After training, the model was evaluated on the testing dataset to obtain the final test accuracy. The model performance was visualized using **Accuracy vs Epoch** and **Loss vs Epoch** graphs, which helped to understand the learning behavior and identify possible overfitting or underfitting.

PART D: Using Hugging Face Pre-trained Models

In this part, a pre-trained vision model from **Hugging Face** was loaded and used to perform image classification on sample images. The predictions obtained from the Hugging Face model were compared with the predictions from the transfer learning model implemented in Part B. The observations were documented based on the classification results and model performance. Finally, the complete notebook, code, results, graphs, and README file were organized and uploaded to **GitHub** for documentation and submission.
# 24ADI006_RAMYA-R_24BAD096_DL_EX_4
