# Plant Classifier

This Python notebook contains a plant classifier model trained on a dataset of fruits. The model is built using TensorFlow and Keras, and it uses a MobileNetV2 architecture pre-trained on ImageNet.

## How to Use

1. **Prepare the Dataset**: The dataset should be organized into three directories: `Train_Set_Folder`, `Validation_Set_Folder`, and `Test_Set_Folder`. Each directory should contain subdirectories for each class, and the subdirectories should contain the images for that class.

2. **Run the Notebook**: Run the cells in the notebook in order. The notebook will load the dataset, preprocess the images, and train the model.

3. **Evaluate the Model**: The notebook includes code to evaluate the model's performance on the test set and display a confusion matrix.

4. **Make Predictions**: The notebook includes code to make predictions on new images. To make a prediction on a new image, replace `'test_img/banana.jpg'` with the path to your image.

5. **Use the Model with a Webcam**: The notebook includes code to use the model with a webcam. The code captures frames from the webcam, makes predictions on the frames, and displays the predictions on the frames in real-time. To stop the webcam feed, press 'q'.

## Requirements

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Note

The model is saved as `model.keras` after training. You can load this model using `keras.models.load_model('model.keras')`.