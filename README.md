Lung Cancer Prediction Project




This project aims to predict lung cancer using both image-based deep learning and text-based machine learning models. It compares the performance of these approaches using various evaluation metrics to identify the most effective solution.

🧠 Approaches Used
Image-based Prediction: Utilizes Convolutional Neural Networks (CNN) to analyze CT scan images.
Text-based Prediction: Uses structured patient data and applies machine learning models like Random Forest, SVM, and Logistic Regression.
📊 Evaluation Metrics
Models are evaluated based on:

Accuracy
Precision
Recall
F1 Score
📦 Requirements
Install the required dependencies using:

pip install -r requirements.txt
If you're working with image data, install and configure Git LFS:

bash
Copy
Edit
git lfs install
git lfs pull
💡 Key Highlights
CNN model achieved the highest accuracy and F1 score for image-based prediction.

Random Forest and SVM performed well on structured data.

Includes detailed preprocessing, training, and evaluation steps.

📁 Dataset
Image-based: CT scan images of lung tissue (stored with Git LFS).

Text-based: Tabular data including patient attributes and diagnosis.

👤 Author
Mohan Krishna R
GitHub: moha-n-ctr
