# PRODIGY_ML_03
I developed a machine learning model to classify images of cats and dogs using a Support Vector Machine (SVM) classifier. The dataset used was the Cat and Dog Dataset from Kaggle, which contains labeled images of cats and dogs in JPEG format.

The goal of the project was to build an accurate image classification model using traditional machine learning techniques (without deep learning). The workflow included the following steps:

Data Collection: The dataset was organized into separate folders for cats and dogs.

Preprocessing: Each image was converted to grayscale and resized to a fixed dimension to ensure consistency across inputs.

Feature Extraction: I used HOG (Histogram of Oriented Gradients) to extract important edge and shape-based features from the images.

Labeling: Images were labeled numerically — 0 for Cat and 1 for Dog — for supervised learning.

Train-Test Split: The dataset was divided into training and testing sets using an 80-20 split.

Model Training: An SVM classifier with a linear kernel was trained using the extracted HOG features.

Evaluation: The model’s performance was evaluated using accuracy score and classification metrics, and it achieved high accuracy in distinguishing between cats and dogs.

Model Saving: The trained model was saved using both pickle and joblib for future reuse.

Prediction: A utility function was created to predict new images using the saved model.

Development Environment: The entire project was implemented using Jupyter Notebook.

This project helped me gain hands-on experience with image preprocessing, feature engineering, and SVM-based classification. It also enhanced my understanding of applying classical machine learning algorithms to real-world image datasets.
