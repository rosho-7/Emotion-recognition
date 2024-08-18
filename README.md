The Jupyter notebook does mention the use of LSTM for training. Here is a refined README file considering that LSTM is used for training:

---

# Toronto Emotional Speech Set (TESS) - Python Project

This Python project leverages the Toronto Emotional Speech Set (TESS) dataset to analyze and classify emotional speech. The dataset consists of audio recordings of 200 target words spoken in seven different emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral).

## Dataset

The dataset can be accessed from [Kaggle: Toronto Emotional Speech Set (TESS)](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess).

## Prerequisites

Ensure you have the following libraries installed before running the notebook:

- pandas
- numpy
- seaborn
- matplotlib
- librosa
- IPython
- tensorflow
- keras

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib librosa IPython tensorflow keras
```

## Project Structure

The project is structured as follows:

1. **Data Loading and Exploration:**
   - Load the dataset and explore its structure.
   - Visualize the distribution of emotions in the dataset.

2. **Audio Processing:**
   - Extract features from the audio recordings such as Mel-frequency cepstral coefficients (MFCCs).
   - Visualize audio features using spectrograms.

3. **Model Training with LSTM:**
   - Train a Long Short-Term Memory (LSTM) neural network to classify the emotions in the audio recordings.
   - Evaluate the performance of the LSTM model using appropriate metrics.

4. **Results and Analysis:**
   - Present the results of the model evaluations.
   - Analyze the misclassifications and potential improvements.

## Conclusion

This project demonstrates how to work with the Toronto Emotional Speech Set (TESS) dataset using Python for audio processing and emotion classification. The notebook includes steps for loading data, extracting features, training LSTM models, and evaluating performance.
