# MLPR-Lab5
MLPR LAB 5 — SPRING 2026

## Aim
To detect faces in an image and cluster them using HSV color features and K-means clustering.

## Methodology
- Face detection using Haar Cascade classifier
- Conversion of detected faces to HSV color space
- Extraction of Hue and Saturation features
- K-means clustering of face features
- Classification of a template image using trained clusters

## Tools Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Results
Faces were successfully detected from the faculty image.
K-means clustering grouped faces into two clusters based on HSV features.
The template image was classified into the nearest cluster using the trained model.

## Conclusion
This lab shows how feature extraction and distance-based clustering can be used for image-based classification tasks.
