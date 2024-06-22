# Techstraver-MachineLearning

## Voice Command Recognition

### Problem Statement

Develop a voice command recognition system that detects the language in audio and translates speech from any language into English.

### Implementation

1. **Library Requirements**:
   - Use `speech_recognition` for audio recognition.
   - Implement language detection with `langdetect`.
   - Translate detected language to English using `googletrans`.

2. **Steps to Implement**:
   - Utilize `speech_recognition` to transcribe audio files.
   - Implement language detection to identify the language of the speech.
   - Translate the speech into English using `googletrans`.
   - Print the detected language, original text, and translated text.

## Gender and Age Detection with OpenCV

### Problem Statement

Develop a computer vision application using OpenCV that accurately predicts the gender and age of individuals from images.

### Implementation

1. **Model Requirements**:
   - Download pre-trained models for face detection, gender classification, and age estimation.
   - Models can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1Lb0bRQj-Tdrn5LFy9UjNMfd8r4Tp6UIb).

2. **Steps to Implement**:
   - Use OpenCV's `dnn` module to load the pre-trained models.
   - Process images to detect faces, classify gender (male or female), and estimate age ranges.
   - Display the input image with bounding boxes and predicted labels (gender, age).

## Stock Price Prediction for Microsoft Corporation (MSFT)

### Problem Statement

Examine the stock price of Microsoft Corporation (MSFT) from NASDAQ and build an LSTM model to predict future stock prices.

### Implementation

1. **Data Collection**:
   - Obtain historical stock data for MSFT from NASDAQ.
   - Perform data preprocessing and feature engineering.

2. **Model Building**:
   - Build an LSTM model using Keras to predict stock prices.
   - Compile and train the model using appropriate parameters.
   - Evaluate the model's performance using metrics such as mean squared error (MSE) and R-squared.

3. **Prediction and Visualization**:
   - Make predictions using the trained model.
   - Plot true values vs. predicted values to visualize the model's accuracy.

## License

This project is licensed under the [MIT License](LICENSE).
