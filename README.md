# ImageTextRecognition

## Problem Statement
Given an input Image we need to predict the Text in the Image with a reasonable accuracy >80% (Exact match with the actual Text Labels) 
and should have a good letter match accuracy.

## Performance Metrics
*	Accuracy
*	Letter Accuracy
*	CTC Loss

## Model Architecture
The architecture consists of three parts:
1. convolutional layers, which extract a feature sequence from the input image;
2. recurrentlayers, which predict a label distribution for each frame;
3. transcription layer, which translates the per-frame predictions into the final label sequence

Please check my iPython Notebook for detailed analysis and implementation of this project.

## Blog
I have written a Medium Blog giving a detailed explaination of the implementation. Do feel free to read it.
https://medium.com/analytics-vidhya/image-text-recognition-738a368368f5




