# Classification-Gender-Voice-Recognition
Classification and Clustering of Gender by Voice Recognition Using NN, SVM, Naive Bayes, and Agglomerative Algorithms in Python.

Oral language is the most natural way for humans to convey information. Speech signals provide several different types of information. From a speech point of view, it conveys speech signals, linguistic information (eg message) and speaker information (eg emotional, regional and physiological characteristics). From the point of view of speech perception, it also provides information about the environment in which speech is produced and transmitted. Even though this wide range of information is encoded in a complex form of a speech signal by a human voice device, humans can easily decrypt much of information. The existence of such an ability in humans has inspired many researchers to understand speech in order to develop systems that automatically learn and process this information. This technology has found wide applications such as **automatic dictation**, **voice command control**, **voice archive indexing**, **Voice retrieval** and so on.

This Project contains two phases of **Data Collection*, **Data Preprocessing**, and **Classification**.

* ### Data Collection
  In this phase we collected a data set from 10 students voices reading 10 distinct scientific texts with a length of 1 min each. Students were chosen from males and females equally.

* ### Data Preprocessing
  Recorded voices are always subject to different types of noises due to background noises, microphone quality, etc. In this step we omited unwanted added signals using digital filters (FIR, IIR) and frequency domain analysis. Also, by delleting the possible silence gaps in recorded voice, we increased the quality and accuracy of the data set.

* ### Classification
    
  we exctracted and used five independent groups of features from the data set
    1. MFCC (Mel-Frequency Cepstral Coefficients)
    2. Chromagram
    3. Spectrogram-Mel
    4. Contrast
    5. Tonnetz
    
  After preparing the data matrix, we shuffled the samples and considered 70% of the samples as training data set, 20% as validation data set and 10% for testing. We set aside the test data for final evaluation and used the training data to classify the desired classes and to validate the hyper parameter data set.
  * #### Classifiers:
    * Neural network
    * Linear SVM
    * polynomial SVM
    * Naïve Bayes


 <p align="center">
<img src="https://user-images.githubusercontent.com/40741680/125693034-1f944c49-d303-4e2a-b30d-c1b870c12af0.png" width="480" height="300" align="center">
  <img src="https://user-images.githubusercontent.com/40741680/125693295-982e8ebc-613f-41f1-9edf-e6782c4e1fbc.png" width="480" height="300" align="center">

 </p>

