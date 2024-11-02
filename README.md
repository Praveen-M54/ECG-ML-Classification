# ECG-ML-Classification

This project contains Jupyter notebooks that help you download the publicly available [MIT-BIH Arrhythmia Database](https://physionet.org/physiobank/database/mitdb/), and do some Machine Learning on it inorder to predict if the heart-beats in the ECG data classify either as "Normal" or "Abnormal".

Many training models on ECG data seem to work around building out a Convolutional Neural Network (CNN) in Keras.

- A [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network) is typically used for classifying image data.
- [Keras](https://keras.io/) is the API that makes building such a neural network relatively easy.

The model in this project instead uses [Tensorflow Estimators](https://www.tensorflow.org/guide/estimators).

More details are included in each of the notebook files.

# Used Libraries

- [Python](https://www.python.org/)
- [NumPy](https://docs.scipy.org/doc/numpy/dev/)
- [Matplotlib](https://matplotlib.org/)
- [wfdb](https://pypi.org/project/wfdb/)
- [mitdb](https://github.com/Nospoko/qrs-tutorial) - To make the code in "datasets" and "utils" compatible with Python 3, add parentheses to print statements and replace import urllib2 with import urllib.request as urllib2.
- [BioSPPy](https://github.com/PIA-Group/BioSPPy)
- [Tensorflow](https://www.tensorflow.org/)

# Disclaimer

Do not use anything from this project to make medical decisions. It is for educational and learning purposes only.
