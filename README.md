# music-genre-classification
The objective of this project is to perform music genre classification through the application of cutting-edge deep learning techniques. Specifically, a convolutional neural network (CNN) is leveraged to extract high-level features from audio files, which are subsequently used to classify them into pre-defined genres.
# Dataset
The dataset employed in this project is the well-known GTZAN dataset, which is a benchmark dataset widely used in music genre classification tasks. The dataset comprises a total of 1000 audio files, each of which is 30 seconds long. Specifically, the dataset contains 10 different music genres, with each genre having exactly 100 audio files. These genres encompass a diverse range of musical styles, including : 

* Blues
* Classical
* Country
* Disco
* Hip-hop
* Jazz
* Metal
* Pop
* Reggae
* Rock

The inclusion of such a wide variety of genres ensures that the dataset is representative of the musical landscape and enables the algorithms to learn the nuances of each genre in a comprehensive and balanced manner. Additionally, the relatively large size of the dataset provides ample data for training and testing the classification algorithms, which is critical for achieving high accuracy and generalizability.
# preprocessing
Prior to being used as input for classification algorithms, the audio files underwent a preprocessing step whereby they were transformed into a Mel-frequency cepstral coefficients (MFCCs) format. This process involved a mathematical transformation that condensed the audio data into a more compact and manageable representation. The MFCCs representation is particularly effective at capturing the spectral envelope of a sound signal, which is a key factor in distinguishing between different audio signals. By representing the audio data in this way, it became easier to extract meaningful features from the audio files and use them as input for the classification algorithms. Ultimately, the use of MFCCs as input for the classification algorithms improved the accuracy of the music genre classification task and enabled the algorithms to make more informed decisions based on the spectral characteristics of the audio data.
# classificaation algorithms
This project employed several classification algorithms to classify music genres with the goal of determining the most accurate method following some :

Logistic Regression is a linear regression-based classification algorithm that is often used for binary classification problems. It is simple yet effective and is particularly useful when the input data is linearly separable. Logistic Regression was used in this project to classify the music genres based on the extracted features.

AdaBoostClassifier is an ensemble learning algorithm that combines several weak learners to produce a strong learner. It is particularly useful for classification problems and can be used with various base classifiers. AdaBoostClassifier was used in this project to classify the music genres by boosting the performance of several weak classifiers.

CatBoostClassifier is another ensemble learning algorithm that can handle categorical data and perform well in noisy and unbalanced datasets. It is particularly useful for classification problems and has been used in various machine learning competitions. In this project, CatBoostClassifier was used to classify the music genres based on the extracted features.

K-Nearest Neighbors (KNN) is a non-parametric classification algorithm that is particularly useful when the training data is small. It is simple yet effective and can be used for both binary and multi-class classification problems. KNN was used in this project to classify the music genres based on the similarity of the extracted features.

Libraries used The following libraries were used in this project:

librosa: for audio file loading, feature extraction, and manipulation
scikit-learn: for machine learning models and evaluation metrics
numpy: for numerical computations
pandas: for data manipulation and analysis
seaborn and matplotlib: for data visualization
# Model
The model used for this project is a CNN with three convolutional layers, two pooling layers, and two dense layers.
# Usage
To use this project, you need to install the required libraries using the following command: pip install -r requirements.txt

Once you have successfully installed the necessary libraries, you can proceed to open the Jupyter Notebook file named Music_Genre_Classification.ipynb in order to initiate training and testing of the model. Moreover, you have the flexibility to modify the hyperparameters within the notebook to conduct experiments with varied settings, thereby allowing for a more comprehensive analysis.
# Conclusion
In summary, this project showcases the efficacy of utilizing deep learning techniques and classification algorithms in the task of music genre classification. The findings are highly encouraging, underscoring the enormous potential of such methods in this domain. Moreover, the project serves as a valuable foundation for further explorations and investigations in this field, paving the way for future research endeavors.
