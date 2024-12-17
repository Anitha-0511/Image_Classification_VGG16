
Model:https://storage.googleapis.com/tensorflow/keras-applications/vgg16/vgg16_weights_tf_dim_ordering_tf_kernels_notop.h5

Streamlit Weblink:"https://37e9-35-245-228-171.ngrok-free.app"

Objectives:

Utilize VGG16 for Feature Extraction:

● Employ the VGG16 model, excluding its top layers, to serve as a feature extractor for cat and dog images.

● Ensure the input images are of the correct size (150x150) and preprocessed appropriately to match VGG16’s requirements.

Data Preprocessing and Augmentation:

Implement image data generators for real-time data augmentation, ensuring a robust and varied dataset for training the classification layers.

Build and Train the Classification Model:

● Add custom fully connected layers on top of the VGG16 model for the classification task.

● Freeze the convolutional layers of VGG16 to retain the pre-trained features and only train the added classification layers.

Model Compilation and Training:

● Compile the model using stochastic gradient descent, categorical cross-entropy as the loss function, and accuracy as the evaluation metric.

● Train the model using the training data, and validate its performance using a validation set.

Evaluate and Test the Model:

Assess the model’s performance based on its accuracy in classifying images into cat or dog categories.

Implement a prediction function to classify new images, providing the predicted category and the associated confidence level.

<img width="458" alt="image" src="https://github.com/user-attachments/assets/c5cd083e-0c8b-4967-aed3-f1703dc83072">
















