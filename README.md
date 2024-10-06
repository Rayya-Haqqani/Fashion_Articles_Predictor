This project aims to classify images of various clothing articles using a neural network built with Keras.

#### **Key Steps:**
1. **Data Preprocessing**: Load the dataset and normalize pixel values to a range of 0 to 1.
2. **Model Architecture**: 
   - Flatten the images into a 1D array.
   - Use a hidden layer with 128 neurons (ReLU activation).
   - Implement an output layer with 10 neurons (softmax activation).
3. **Model Compilation**: Compiled the model using the Adam optimizer and sparse categorical cross-entropy loss.
4. **Training**: Trained the model for 8 epochs.
5. **Evaluation**: Test accuracy achieved is **88%**.

This project demonstrates the effectiveness of deep learning in image classification tasks.
