# Brain_cancer-tumor_classification
 The dataset  we have used contains 7023 images of human brain MRI images which are classified into 4 (5712 images to train model ,1311 images to test model)​
 classes: glioma, meningioma, and pituitary.
for model Building we have considered above 3 classes 
## Data Preparation 
 Load the data (Brain MRI )
 
 Pre-processing images(noise removal, resize)
 
 Append images and labels into Python list
 
 Convert lists into numpy array
 
 normalize images and Encoding on the labels
 
 Dividing the dataset into Training and Validation and Testing sets.
 
it reads the image using cv2.imread() and loads it in grayscale mode

The cv2.bilateralFilter() function is applied to the image to remove noise. This filter is a type of edge-preserving, noise-reducing filter.

The cv2.applyColorMap() function is used to produce a pseudocolored image. The colormap chosen here is cv2.COLORMAP_BONE, which maps grayscale values to a bone-like color palette.
## MODELS
Machine learning models : 
    Logistic Regression , SVM
   
Simple neural networks

convolutional Neural networks

Transfer learning models
 ## we got training accuracy for our final model(ResNet50) is 98.99 and testing accuracy is 98.88
