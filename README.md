## Speech Emotion Recognition
Developed a Speech Emotion Recognition system using the RAVDESS dataset to classify human emotions from
audio signals. Implemented and compared multiple machine learning models with progressive improvements in
performance across models. Utilized MLflow to track experiments, visualize performance metrics, and compare
model results based on accuracy and F1-score.

## Models Used:
- Logistic Regression
- MLP (Neural Network)
- Random Forest
- LightGBM
## Features:
- Audio preprocessing using Librosa
- MFCC feature extraction
- Model comparison
- Visualization of results
- Experiment tracking using MLflow
## Project Structure:
- speech_emotion.ipnyb 
- outputs/ - graphs and results
- requirements.txt - dependencies

## Dataset:
This project uses the RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset.

Download it from:
[https://zenodo.org/record/1188976](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)
After downloading place it inside:
data/

## How to Run:
Create a virtual environment inside the project folder then follow the steps below:

1. Install dependencies:
pip install -r requirements.txt

2. Run the notebook:
speech_emotion.ipynb

## Results:
Check the outputs/ folder for:
- Confusion matrices
- PCA visualizations
- Model comparison graphs

MLflow:
To view MLflow run the commands given in the notebook on the terminal 

Then open:
http://localhost:5000

## Note:
Dataset and preprocessed files are not included due to size constraints.
