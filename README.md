 Bones usually break if it’s attacked in a certain area of life, therefore Bone fracture detection is a highly important 
task in medical image analysis where most experts is required to differentiate of bones fracture from X-ray images. 
In this research, we look at how we can automate this process with the help of machine learning techniques, and 
present an efficient and accurate manner to do so for clinical settings. We trained multiple classifiers including 
classical (Support Vector Machine SVM and Random Forest RF) and deep learning models ResNet50, VGG16, and 
EfficientNet to classify X-ray images on two labels, i.e. fracture and non fracture. During the training and evaluation 
phase, a dataset of labeled X-ray images having their fracture binary labelled was used. To assess the effectiveness 
of the models, we used such metrics as accuracy, precision, recall, and F1 score. We find that EfficientNet yields the 
best performance (accuracy of 99.01%, good precision, recall and F1). We also examined dimensionality reduction 
techniques for additional refinement to model performance such as Principal Component Analysis (PCA) and Linear 
Discriminant Analysis (LDA). The results demonstrate how deep learning models, in particular EfficientNet, can bring 
faster and practical solutions in medical image classification and can serve as an inspiration for future research in the 
development of automated fracture detection systems. 
