# Plant-Disease-Detection
Plant Disease Detection Using Deep Learning


Description

This project implements machine learning algorithms and deep learning for the classification of plant disease for finding the best accuracy stored in dataset of plant disease images of rice, pepper bell, potato and tomato. All these data are combination of binary and multi-class problem.

Data sets for Rice:  https://archive.ics.uci.edu/ml/datasets/Rice+Leaf+Diseases

Data sets for Pepper Bell, Potato and Tomato: https://www.kaggle.com/emmarex/plantdisease

Initially the data is collected in the image form. Load the images name with class in a csv file into WEKA. Then convert the images name to string and class name to nominal, it will produce the arff file. Using the package of WEKA called  imageFilters, use the converted arff file as an input to imagefilters called AUTO COLOR CORRELOGRAM. Once the filter is applied use the attribute for conversion String to Nominal.

Once the image filters step is completed, using the file to apply the classfication algorithms in WEKA along with Deep Learning4j. 




 
  
 
 
  
  
 



