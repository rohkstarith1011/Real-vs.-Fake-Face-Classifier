# Real vs. Fake Face Classifier

This project implements a machine learning application that classifies images of faces as "real" or "fake" using a Support Vector Machine (SVM) model. The application features a user-friendly interface built with Tkinter, allowing users to upload images and receive instant predictions.

## Features

- **Image Upload**: Easily select and classify images of faces.
- **Real-time Predictions**: Displays classification results immediately after image selection.
- **Image Information**: Shows the uploaded image name and dimensions.
- **Clear Functionality**: Clear the displayed image and results with a single click.
- **Error Handling**: Gracefully manages errors during image processing.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Scikit-learn
- Pillow
- Tkinter (usually included with Python)

## Installation
 **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/real-vs-fake-face-classifier.git
   cd real-vs-fake-face-classifier
Install Required Libraries: You can install the necessary libraries using pip:

pip install opencv-python numpy scikit-learn pillow
Download the Dataset: To train the SVM model, you will need a dataset of real and fake faces. Follow these steps:

Go to Kaggle.
Search for a dataset containing images of real and fake faces. A popular choice is the "Real and Fake Faces" dataset.
Download the dataset to your local machine.
Extract the dataset, and organize the images into two folders: real and fake.
Your folder structure should look like this:

sql
Copy code
├── real-vs-fake-face-classifier/
│   ├── real/
│   │   └── (real face images)
│   ├── fake/
│   │   └── (fake face images)
Train the SVM Model:

Run the training script (train_model.py) to create and save the SVM model:
Launch the GUI application:
Click the "Select Image" button to upload a face image.

View the classification result and image information displayed on the screen.

Use the "Clear" button to reset the interface for another image.
Thanks to the libraries and tools that made this project possible, including OpenCV for image processing and Scikit-learn for machine learning.

Feel free to customize any part of the README to better match your project specifics or personal preferences!

This README provides clear instructions on how to set up and use your project, making it accessible to various users.
