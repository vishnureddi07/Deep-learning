# Deep-learning
Deep learning is a subset of Machine Learning (and a broader part of Artificial Intelligence) that mimics the way the human brain processes data. While traditional machine learning requires humans to manually "teach" the computer which features to look for, deep learning uses Artificial Neural Networks to automatically discover these patterns.

How it Works: The Neural Network
Deep learning is called "deep" because it uses many layers of interconnected "neurons."

Input Layer: Receives raw data (like the pixels of a photo).

Hidden Layers: This is where the magic happens. Multiple layers of neurons perform mathematical calculations to identify features. For example, in image recognition, the first layer might find edges, the next might find shapes, and a deeper layer might identify a face.

Output Layer: Provides the final prediction (e.g., "This is a cat").

Binary ANN:
Overview of the Implementation
The notebook follows a standard deep learning workflow for binary classification:

Data Loading and Preprocessing:

Dataset: It uses a breast cancer dataset (breast-cancer (1).csv) containing 569 rows and 33 columns.

Cleaning: The code removes unnecessary columns like Unnamed: 32 and id.

Encoding: The target variable diagnosis is mapped to binary integers, where 'M' (Malignant) is 1 and 'B' (Benign) is 0.

Libraries: It utilizes standard Python libraries including numpy, pandas, matplotlib, seaborn, and sklearn.

Model Architecture & Performance:

The notebook builds an ANN designed for binary output.

Evaluation: The model achieves an accuracy score of approximately 94.7% on the test set.

Results: The confusion matrix shows high precision, correctly identifying 13 instances of one class and 5 of the other, with only 1 misclassification in the displayed output.

Key Metrics from the Notebook
Final Accuracy: 0.9473684210526315 (approx. 94.7%).

Confusion Matrix: [[13, 0], [1, 5]].

This implementation demonstrates a practical application of deep learning for medical diagnostic classification using a supervised learning approach.
