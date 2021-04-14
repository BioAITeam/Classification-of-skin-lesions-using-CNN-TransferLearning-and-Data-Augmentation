# Classification of skin lesions using Convolutional Neural Networks, TransferLearning and Data Augmentation

One of the most potent diseases we can find today is cancer. In this work, we focused on pigmented reticular skin cancer, and although for now there are treatments that manage to save lives, many of these are either very new, in study stages, or do not work when the disease is already advanced. There is a tendency to use alternative methods to detect it at the right time and apply a treatment. This work is based on digital image processing and Deep Learning to obtain more significant characteristic parameters. With the design, a classification model employing convolution neural networks improved and adapted to our problem provides aid in pigment diagnosis, detecting cancer, and the type of skin lesion. We will make use of pre-trained models of Keras in order to find a model compatible with dermatological images and to be able to improve this model, adapting it and obtaining results above 95\%.

## Folders
- **Data_Augmentated** This folder contains the notebooks for the data increment of the HAM10000 and ISIC 2019 databases.
- **Models** this folder contains the models used for the training of the databases mentioned above.


## Requirements
This repository requires the following libraries and frameworks:

- TensorFlow 
- scipy
- scikit-learn
- Datetime
- numPy 
- OpenCV 
- Yellowbrick
- Matplotlib
- Time
- random
- os
- scikit-image
- glob

This repository was developed in the Python3 (3.8) programming language.

## Package installation

if you don't use google colab, We highly recommend to use and install Python packages within an Anaconda enviroment. To create, execute the command below:
```
conda create --name Improving python=3.8
```
So, activate it
```
conda activate Improving
```
installed the framework
```
conda install -c anaconda keras-gpu==2.4.3
```
Now, install the libraries.
```
pip install tensorflow
pip install opencv-python
conda install -c conda-forge matplotlib
conda install -c anaconda scipy
conda install -c jmcmurray os
conda install -c conda-forge time
conda install -c anaconda scikit-image
conda install -c anaconda scikit-learn
conda install -c trentonoliphant datetime
conda install -c districtdatalabs yellowbrick
```

## Authors
Universidad Autonoma de Manizales (https://www.autonoma.edu.co/)

- Juan Pablo Villa Pulgarin
- Anderson Alberto Ruales Torres
- Daniel Arias-Garzón
- Alejandro Bravo Ortiz
- Harold Brayan Arteaga Arteaga
- Jesus Alejandro Alzate Grisales
- Simon Orozco Arias
- Oscar Cardona-Morales
- Reinel Tabares Soto


South Valley University (https://www.svu.edu.eg/en/)
- M. Hassaballah

## References

[1] PAPER CANCER



# Database 
Ham10000 database
## https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/DBW86T/GQGSWO&version=2.0
ISIC 2019 database
## https://challenge2019.isic-archive.com/data.html
