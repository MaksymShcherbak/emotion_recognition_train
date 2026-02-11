# Emotion Recognition 🐵

Recognizing emotions is something we as humans intuitively do - it's vital for our survival.

But how do we teach a computer to do the same?

![example1](example1.png)

_This is the repository for the Jupyter Notebook. If you're looking for the source code of the Web App, check out [https://github.com/MaksymShcherbak/emotion_recognition_web](https://github.com/MaksymShcherbak/emotion_recognition_web)_

This was my **Bachelor's Degree** project at university.

## Tech Stack

- 🐍 [Python](https://www.python.org/) as the most popular Programming language in the ML field.
- ⚡ [Keras/TensorFlow](https://keras.io/) Framework for building and training deep learning models.

## Models

There are three models described in the Notebook:

- Dense
- CNN
- MobileNetV2

## Setting Up the Environment

If you want to build the project locally, you can use **Anaconda** to create the environment.

1. Install [Anaconda](https://www.anaconda.com/products/distribution).

2. Create the Conda environment using the provided `environment.yml` file:

```bat
conda env create -f environment.yml
```

3. Activate the environment:

```bat
conda activate tf-er-env
```

_If you encounter any issues while running the project on Windows, your system Python user packages may be leaking into the Conda environment._

To prevent this, disable Python user site-packages:

```bat
setx PYTHONNOUSERSITE 1
```

## Training the Models

Execute the `emotion_recognition.ipynb` Notebook to train the models.
