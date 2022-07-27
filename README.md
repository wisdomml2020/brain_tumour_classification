# Brain Tumor Classification from MRI images using ResNet 50 Model

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, XceptionNet
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Project Highlights
<pre>
1. Detected Brain tumors in Brain MRI images using Finetuned ResNet-50 model with 5712 training images (Glioma : 1321 images, Meningioma : 1339 images, Pituitary: 1457 images, No Tumor/Healthy: 1595).
2. For classifying Glioma, Meningioma, Pituitary and Normal classes architecture of pretrained network ResNet50 utlized.
</pre>

#### Dataset
<pre>
Dataset    : <a href=https://drive.google.com/drive/folders/1Pj61qQNfG1Ea7jTD8PK-COXc7MEHbfyo?usp=sharing>Brain Tumor MRI Dataset </a>                  
</pre>
The sample images of Glioma, Meningioma, Pituitary and Normal patients are shown in figure below:
![Image of Brain MRI](https://i.ibb.co/sH3g2Vz/bt1.png)

<pre>
<b>Dataset Details</b>
Dataset Name            : Brain Tumor MRI Dataset (Glioma vs Meningioma vs Pituitary vs Normal)
Number of Class         : 4
Number/Size of Images   : Total      : 7023 (151 MB)
                          Training   : 5712 
                          Testing    : 1311 
                         
</pre>
#### Results
We have achieved following results with Resnet-50 model for detection of Glioma, Meningioma, Pituitary and Normal patients from Brain MRI images.

<pre>
<b> Performance Metrics </b>
Test Accuracy                                    : 98.86%
Precision                                        : 99.00%
Sensitivity (Glioma)                             : 97% 
Sensitivity (Meningioma)                         : 99% 
Sensitivity (Pituitary)                          : 100% 
Sensitivity (Normal)                             : 100% 
F1-score                                         : 99.00%
AUC                                              : 1.0
</pre>
