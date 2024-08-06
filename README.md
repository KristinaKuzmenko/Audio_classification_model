## Audio Classification using Fourier Transform and KNN

# Project Description:

In this project, I developed an audio classification model to distinguish between different sound categories using the "ESC-50" dataset. The dataset includes various environmental sound recordings, and for this project, I focused on classifying sounds of 'dogs' and 'chirping birds'.

# Key Steps and Highlights:

- # Data Acquisition and Preparation:

- Downloaded and extracted the "ESC-50" dataset.
- Selected sounds with labels 'dog' and 'chirping_birds', and encoded these categories numerically.
- # Feature Extraction:

- Implemented a function to convert audio samples into spectrograms using the Short-Time Fourier Transform (STFT).
- Extracted key features from audio signals to create feature vectors suitable for classification.
-  # Dimensionality Reduction and Visualization:

- Reduced feature dimensionality using Principal Component Analysis (PCA) for visualization.
- Created scatter plots to visualize the distribution of features and the clustering of different sound categories.
# Model Development and Evaluation:

- Experimented with different distance metrics (Euclidean, Manhattan, Cosine) in K-Nearest Neighbors (KNN) classification.
- Evaluated model performance using accuracy, precision, recall, and F1 score.
- Achieved the highest accuracy of 93.8% and F1 score of 0.9375 using the Cosine distance metric.
## Conclusion:

- Demonstrated that Fourier Transform-based feature extraction is effective for audio classification tasks.
- Highlighted the importance of selecting appropriate distance metrics for improving classification performance in KNN models.
# Technologies Used:

- Python (Librosa, Pandas, Numpy, Scikit-learn)
- Data Visualization (Matplotlib, Seaborn)
- Audio Processing and Feature Extraction