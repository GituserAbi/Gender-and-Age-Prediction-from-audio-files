# Gender-and-Age-Prediction-from-audio-files

ML-model: GENDER AND AGE DETECTION FROM AUDIO 
The major steps involved are:

Data Collection
Data Pre-processing
Feature Engineering
Model Selection
Model Analysis


Major package - LIBROSA:
Librosa helps to visualize the audio signals and also do the feature extractions in it using different signal processing techniques.

Libraries:
Numpy, pandas, matplotlib, seaborn, sklearn

Data Collection:
The dataset is read as a csv file, visualized in terms of gender and age range to find out the imbalance

Data Pre-processing:
Check null values and proper indexing to extract features

Feature Engineering:
Feature Extraction - It includes the spectral features centroid, bandwidth, rolloff and Mel frequency cepstral coefficients
Feature Transformation - Feature scalability, Encoding
Feature Selection - ANOVA (ANalysis Of VAriance)

Model Selection:
Two classfiers considered are Support Vector Machine and Random Forest

Model Analysis:
The models are evaluated using K-Fold Cross-Validation technique,Grid Search is used.
Confusion matrix built determines the prediction of classes and percentage of error





