# Hand_sign_prediction
Problem statement: Create a Deep learning model to predict the different hand signs images.

Context: Sign languages (also known as signed languages) are languages that use manual
communication to convey meaning. This can include simultaneously employing hand
gestures, movement, orientation of the fingers, arms or body, and facial expressions to
convey a speaker's ideas.
Source: https://en.wikipedia.org/wiki/Sign_language
Dataset – Download from
https://www.kaggle.com/datasets/ardamavi/sign-language-digits-dataset
Note - Use np.load() to read .npy files
Details of datasets:
1. Image size: 64x64
2. Color space: Grayscale
3. File format: npy
4. Number of classes: 10 (Digits: 0-9)
Steps to consider:
1. Normalize images by dividing pixels by 255 (if required)
2. Convert labels to categories (if required)
3. Reshape images so as to fit them to convolution
4. Build a CNN Architecture
5. Execute the model for appropriate number of epochs
6. Depict loss vs. val_loss on line chart.
7. Depict accuracy vs. val_accuracy on line chart.
8. Generate predictions on test_data.
9. Compute Confusion matrix and classification report.
