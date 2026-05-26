# Satellite Image Classification — Urban vs Natural
## Computer Vision Assignment 1 | Problem 3

### Overview
Classical ML-based satellite image classifier using handcrafted
computer vision features. No deep learning used.

### Dataset
EuroSAT RGB Dataset — download from:
https://zenodo.org/records/7711810/files/EuroSAT_RGB.zip

### Features Used
1. Pixel Statistics
2. GLCM Texture
3. LBP (Local Binary Pattern)
4. HOG (Histogram of Oriented Gradients)
5. Edge Density (Canny)
6. Gabor Filter Bank
7. Statistical Moments
8. Hu Moments
9. Colour Channel Ratios
10. Fractal Proxy

### Models
- Logistic Regression
- Random Forest
- SVM (RBF Kernel) ← Best performer

### How to Run
1. Download EuroSAT dataset and place as `EuroSAT/` folder
2. Place your satellite image as `external_test.jpg`
3. Open `satelite_complete.ipynb` in Jupyter or Google Colab
4. Run all cells

### Requirements
pip install opencv-python-headless scikit-image scikit-learn
scipy seaborn tqdm matplotlib numpy pandas
