# Shopee-Code-League-2020
This consists of 2 projects that me and my team attempted. All images and datasets belong to Shopee Code League 2020 with full credits.
## 1. Product Detection

For product detection, we were given a problems consisiting of 100k images. The goal was to create a robust detection system that will improve the listing and categorisation efficiency. My team developed used computer vision to engineer an image classification model via "tensorflow" to determine the correct product categorisations.

### Example of images
 ![CV images](https://github.com/JiaJun98/Shopee-Code-League-2020/blob/main/Product%20Detection/Image_classification(1).PNG)
 
 ### File parsing
 We first accessed the 105,405 files and 44 folders using Python's OpenCV library so that the images can be reshaped into Numpy arrays so that they can be read by other python libaries in our machine learning model. Our team also set up 41 categories(as per stated in the competition) for the OpenCV library to act on too.
 
 ![parsing](https://github.com/JiaJun98/Shopee-Code-League-2020/blob/main/Product%20Detection/OpenCV.PNG)
 
 ### Feature engineering
 Afterwards, we added the features into our X_test to be used to train our machine learning model
 ![ft](https://github.com/JiaJun98/Shopee-Code-League-2020/blob/main/Product%20Detection/Feature%20Engineering.PNG)
 
 

## 2. Sentimental Analysis
