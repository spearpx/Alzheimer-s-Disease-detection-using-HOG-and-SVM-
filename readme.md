# Alzheimer's Disease detection using HOG and SVM

Brain **MRI** contains information about the brains state and behaviour, by using this we can easily detect the severity of Alzheimer's disease (AD). 
Using machine learning (ML) we can create a model that can classify the brain MRI as per the severity. 
### Datasets used in this code have four classes they are : 
- Non Demented
- Very Mild Demented
- Mild Demented
- Moderate Demented

![Brain MRI indicating severity of AD. Top row images from left: Mild Demented, Moderate demented. Bottom row from left Very Mild Demented, Non Demented](https://github.com/spearpx/Alzheimer-s-Disease-detection-using-HOG-and-SVM-/blob/main/brainMRIclasses.jpg?raw=true)

The image gives the brain MRI from each class. From the image it can be seen that the ventricles of brain start to increase in size as the severity of AD increases.
For ML model HOG feature descriptor is used for feature selection and SVM is used as classifier. SVM kernels used are linear, rbf and poly. There are two datasets that the code is tested on, 
both the datasets are available on kaggle. The python notebooks in this repo has the results along with the code. 
For testing the code, download all the files and change the directory of dataset with the path of the directory of the dataset where it is downloaded in the following line:
```
dataset_dir = 'kaggleDataset1/'
```
The parameters can be changed to and tested accordinng to the requirements. 

