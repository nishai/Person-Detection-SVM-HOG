# Person-Detection-SVM-HOG
Person detector using Histograms of Oriented Gradients (HOGs) for feature extraction, and a linear SVM for classification. Done for my Honours _Adaptive Computation and Machine Learning_ project. Includes image data I collected.

## How to run the demo (requires webcam)
 ### Option 1: (may take some time)
  * Run all cells except the ones in the **_Predictions and performance on test set_** section.
  * Run **_Demo_** cell
  
 ### Option 2: (only necessary cells)
  * Run the first 3 cells under **_Loading images with corresponding labels & extracting features using HOG_**.
  * Run both cells under **_Splitting data into training & testing sets_**.
  * Run the cell containing the `Linear_SVM` class cell and the cell under **_Fit SVM on training data_**
  * Run **_Demo_** cell

## Requirements
### Python packages
 * numpy
 * cv2
 * matplotlib
 * scikit-image
 * cvxopt
 * pandas
 * scikit-learn
 * bokeh
