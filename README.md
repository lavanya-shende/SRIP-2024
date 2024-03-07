# SRIP-2024

README

Project Title: ML for Sustainability: Satellite Data Processing for Detecting Pollution Sources

Problem Statement:
Air pollution, particularly from brick kilns, poses a significant threat to public health worldwide. Conventional methods of monitoring brick kilns are expensive and time-consuming. This project aims to revolutionize kiln monitoring by implementing computer vision and machine learning models to efficiently detect brick kilns using low-label satellite imagery. By doing so, the project contributes to effective pollution control and public health preservation.

Code Overview:
The provided code implements various aspects of the project, including dataset preparation, model development, training, evaluation, and visualization. Here's an overview of each section:

Dataset Preparation:

The code organizes the dataset for one-vs-rest classification, binary classification, and 5-class classification.
It utilizes the ImageDataGenerator from Keras for loading and preprocessing images.
The dataset is split into training and validation subsets.
Model Development:

Custom CNN model architecture is designed without using existing architectures like ResNet or DenseNet.
Additionally, the code utilizes the pre-trained VGG16 model for binary classification.
Training and Evaluation:

The models are trained on prepared datasets for one-vs-rest and 5-class classification.
Evaluation metrics such as accuracy are calculated, and classification matrices are generated for visualization.
Convolutional Layer Visualization:

The code includes visualization of the output of all convolutional layers.
Insights on automatically created features are discussed based on the visualization.
Instructions for Use:

Dataset Preparation:

Ensure the dataset is downloaded and stored in the appropriate directory.
Modify the 'folder_path' variable to point to the directory containing animal images.
Adjust parameters such as image dimensions, batch size, and validation split if necessary.
Model Development:

Customize the CNN model architecture as needed.
Explore different architectures or tweak existing ones for better performance.
Training and Evaluation:

Compile the model with suitable optimizer and loss function.
Train the model by specifying the number of epochs and other training parameters.
Monitor training progress and evaluate model performance using provided metrics.
Convolutional Layer Visualization:

Execute the code segment responsible for visualizing convolutional layers.
Analyze the features extracted by different layers and their significance in classification tasks.
Dependencies:

TensorFlow
Keras
NumPy
Matplotlib
Other necessary Python libraries
Conclusion:
The provided code serves as a foundation for implementing machine learning techniques for pollution source detection using satellite imagery. By following the instructions and customizing the code as per specific requirements, users can develop and evaluate models to address similar environmental challenges. Further enhancements and optimizations can be explored to improve model accuracy and efficiency.
