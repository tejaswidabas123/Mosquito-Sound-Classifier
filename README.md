# Mosquito-Sound-Classifier

    CNN Model (get_model3):
        Architecture: A Convolutional Neural Network (CNN) model.
        Input Data: Extracted MFCC features from audio files.
        Key Characteristics: Uses two convolutional layers with max-pooling, dropout, and dense layers. Class weights are used for handling class imbalance.
        Purpose: Training the model for mosquito sound classification.

    1D Convolutional Model (get_model):
        Architecture: A 1D Convolutional Neural Network model.
        Input Data: Processed MFCC features.
        Key Characteristics: Employs a 1D convolutional layer with max-pooling and dropout, followed by dense layers.
        Purpose: Classification of mosquito sounds.

    2D Convolutional Model (get_model2):
        Architecture: A 2D Convolutional Neural Network model.
        Input Data: Processed MFCC features in 2D format.
        Key Characteristics: Utilizes a 2D convolutional layer, flattening, and dense layers.
        Purpose: Mosquito sound classification.

Each of these architectures is used to classify audio data, specifically for identifying mosquito sounds. The choice of architecture (1D or 2D CNN) may influence the model's performance based on the data's format. The models are evaluated for accuracy, and the best model is converted to TensorFlow Lite format for efficient deployment on various platforms.
