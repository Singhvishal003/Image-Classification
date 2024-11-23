## Image Classification Using TensorFlow

This project demonstrates how to create an image classification model using TensorFlow in a Jupyter Notebook to classify images based on emotions.

### Steps Involved:

1. *Setup and Import Libraries*:
   - Import TensorFlow, Keras, NumPy, and Matplotlib.

2. *Load and Preprocess the Dataset*:
   - Load an emotion-labeled image dataset.
   - Split the dataset into training and validation sets.

3. *Build the Model*:
   - Create a Sequential model with Conv2D, MaxPooling2D, Flatten, Dense, and Dropout layers.

4. *Compile the Model*:
   - Use the Adam optimizer and Sparse Categorical Crossentropy loss function.

5. *Train the Model*:
   - Train the model using the training dataset and validate it with the validation dataset.
