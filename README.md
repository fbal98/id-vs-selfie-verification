# Face Verification System

## Quick Overview and Description

This project demonstrates a face verification system that compares a face extracted from an ID card with a face captured from a selfie. The system uses OpenCV for image processing, Dlib for face detection, and the `face_recognition` library for face encoding and comparison. The primary use case is to verify if the person in the selfie matches the person in the ID card photo.

## Built With

- **OpenCV**: For image processing and manipulation.
- **Dlib**: For face detection.
- **face_recognition**: For face encoding and comparison.
- **Google Colab**: For providing the computing environment.

## How to Use

### Prerequisites

Make sure you have the necessary libraries installed. You can use Google Colab to avoid installation issues and leverage GPU acceleration.

### Steps

1. **Set Up Environment**:
   - Open the provided Google Colab link.
   - Switch to GPU acceleration by going to `Runtime -> Change runtime type -> Hardware accelerator -> GPU`.

2. **Install Dependencies**:
   - Run the cells to install necessary libraries (`opencv-python`, `dlib`, and `face_recognition`).

3. **Upload Your Images**:
   - Use the upload cell to upload the ID card image and selfie image.

4. **Extract Frontal Photos**:
   - Run the provided function to extract the frontal photo from the uploaded ID card and selfie images.

5. **Compare Faces**:
   - Run the provided function to compare the extracted faces and determine if they match.

### Link to Google Colab

You can find the Google Colab notebook here: [Google Colab Link](https://colab.research.google.com/github/fbal98/id-vs-selfie-verification/blob/main/test_face_recog.ipynb)

## Built By

Firas Al Kharusi
firas@firasb.com
