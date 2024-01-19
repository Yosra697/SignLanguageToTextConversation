# Sign Language to Text Conversion

## Overview

This project converts American Sign Language gestures into text using neural networks, achieving 98.00% accuracy for the 26 letters of the alphabet.

## Project Description

Designed for communication with Deaf and Mute (D&M) individuals, the system recognizes fingerspelling gestures to form complete words, utilizing computer vision and machine learning techniques.

## Steps to Run the Project

1. **Folder Creation:**
   - Create folders for storing training and testing data.
   - Utilize the provided Python script for folder creation.

2. **Data Collection:**
   - Capture frames from the webcam, define a region of interest (ROI), and apply preprocessing.
   - Use a Gaussian blur filter and adaptive threshold to extract hand gestures.

3. **Model Training:**
   - Employ a Convolutional Neural Network (CNN) for building the model.
   - Train the model on the preprocessed images.

4. **GUI Application:**
   - Create a Graphical User Interface (GUI) for converting signs into text.
   - Use the GUI to communicate with D&M individuals.

5. **Results:**
   - Achieved an accuracy of 95.8% with one layer of the algorithm and 98.0% with a combination of two layers.

## Requirements

Ensure the following Python libraries are installed:

- numpy
- opencv-python
- tensorflow
- keras
- tkinter
- Pillow
- pyenchant
- cyhunspell

## Running the Project

Execute the following command:
```bash
python /path/to/the/Application.py

## Video Demonstration

Watch the [Sign Language To Text Conversation Demo].

![image](https://github.com/Yosra697/SignLanguageToTextConversation/assets/83519787/d9c62551-b4ec-4088-8f9d-7694ba42c568)

![image](https://github.com/Yosra697/SignLanguageToTextConversation/assets/83519787/32da87e0-12ef-479d-addc-84c204de9db3)

![image](https://github.com/Yosra697/SignLanguageToTextConversation/assets/83519787/4f530d8f-cbe5-4aa2-bf75-57e0dd3ca78b)




## Contributors

- [Yosra Sassi](https://github.com/Yosra697)

Feel free to explore and contribute!
