# Speech-Emotion-Recognition
A case study using the already existing SER framework, proposed in https://github.com/IliaZenkov/transformer-cnn-emotion-recognition.
The goal of this research is to quantify the differences of speech datasets and their properties (acted, natural, semi-natural) in a cross validation manner. 
Therefore the IEMOCAP and RAVDESS speech datasets are used. These are two common speech datasets, with RAVDESS being from the acted domain and IEMOCAP being from the semi-natural domain.

In this study the following tests and setups have been done:
1. Trying to recreate the results of the original work by Ilia Zenkov on the RAVDESS dataset. 
2. Training and testing a model on the IEMOCAP dataset. (This is done for comparison reasons)
3. Training a model on the RAVDESS dataset but testing it on the IEMOCAP dataset. (This is done to see if acted datasets can be used to train models that need to be used in real world applications)
4. Training a model on the IEMOCAP dataset but testing it on the RAVDESS dataset. (This is done for comparison reasons)
