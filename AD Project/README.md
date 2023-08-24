# AD Image Classification Project with Machine Learning Procedure and Optimization Considerations


# Project Procedures:
1. Installment and preparation: Please make sure to install all necessary packages (e.g., TensorFlow) and make sure that they run in your local environment (please note that TensorFlow might not work in the Anaconda Jupiter Notebook environment. If that's the case, GoogleColab might be a potential option).

2. Download the ResNet-50 weights from ResNet-50.com for later usages

3. Upload and mount the chosen AD datasets and the ResNet-50 weights into your Google Drive (if chosen to use the Colab environment)

4. Setting up parameters and data generators for the model 

5. Load ResNet-5o pre-trained model and weights 

6. Create and build the model with ResNet-50 with ReLu and Softmax as the hidden and output layer classifiers

7. Compile the model with the 'categorical_crossentropy' function and the Adam optimizer. Make sure to save the best model based on the highest validation accuracy.

8. Train the model with different parameters and save the model weights

9. Retrieve the training and validation accuracy values and plot both 'Accuracy' and 'Loss' for better visualization

10. Create a prediction model by defining a function to predict and classify MRI images 

11. Create a loop to iterate through the directory with image samples for different classes (the number of classes depends on the chosen dataset)

12. Crete a confusion matrix to compare the validation error in different classes


# Potential Optimization methods:

# 1. Fine-tuning: 
Change the optimizer (Adam), change the batch size, change the learning rate, play around with the horizontal flips
# 2. Classes: 
Change the number of classes 
# 3. Balanced dataset: 
Balance the dataset in each class so that the model can learn each of them equally 
