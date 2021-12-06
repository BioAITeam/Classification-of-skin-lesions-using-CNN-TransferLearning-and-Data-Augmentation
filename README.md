# Optimized Convolutional Neural Network Models for Skin Lesion Classification

Skin cancer is one of the most severe diseases, and medical imaging is among the main tools for cancer diagnosis. The images provide information on the evolutionary stage, size, and location of tumor lesions. This paper focuses on the classification of skin lesion images considering a framework of four experiments to analyze the classification performance of Convolutional Neural Networks (CNNs) in distinguishing different skin lesions. The CNNs are based on transfer learning, taking advantage of ImageNet weights. Accordingly, in each experiment, different workflow stages are tested, including data augmentation and fine-tuning optimization. Three CNN models based on DenseNet-201, Inception-ResNet-V2, and Inception-V3 are proposed and compared using the HAM10000 dataset. The results obtained by the three models demonstrate accuracies of 98%, 97%, and 96%, respectively. Finally, the best model is tested on the ISIC 2019 dataset showing an accuracy of 93%. The proposed methodology using CNN represents a helpful tool to accurately diagnose skin cancer disease.

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
- Mario Alejandro Bravo-Ortiz
- Harold Brayan Arteaga-Arteaga
- Alejandro Mora-Rubio
- Jesus Alejandro Alzate-Grisales
- Esteban Mercado-Ruiz
- Simon Orozco-Arias
- Oscar Cardona-Morales
- Reinel Tabares-Soto


South Valley University (https://www.svu.edu.eg/en/)
- M. Hassaballah

## Citing

If you use our project for your research or if you find this paper and repository helpful, please consider citing the work:

Villa-Pulgarin, J. P., Ruales-Torres, A. A., Arias-Garzón, D., Bravo-Ortiz, M. A., Arteaga-Arteaga, H. B. et al. (2022). Optimized Convolutional Neural Network Models for Skin Lesion Classification. CMC-Computers, Materials & Continua, 70(2), 2131–2148. [https://www.techscience.com/cmc/v70n2/44641](https://www.techscience.com/cmc/v70n2/44641)

```
@Article{cmc.2022.019529,
AUTHOR = {Juan Pablo Villa-Pulgarin, Anderson Alberto Ruales-Torres,2, Daniel Arias-Garzón, Mario Alejandro Bravo-Ortiz, Harold Brayan Arteaga-Arteaga, Alejandro Mora-Rubio, Jesus Alejandro Alzate-Grisales, Esteban Mercado-Ruiz, M. Hassaballah, Simon Orozco-Arias, Oscar Cardona-Morales, Reinel Tabares-Soto},
TITLE = {Optimized Convolutional Neural Network Models for Skin Lesion Classification},
JOURNAL = {Computers, Materials \& Continua},
VOLUME = {70},
YEAR = {2022},
NUMBER = {2},
PAGES = {2131--2148},
URL = {http://www.techscience.com/cmc/v70n2/44641},
ISSN = {1546-2226}
}
```

This paper was published as a journal paper in Tech Science Press - Computers, Materials & continua. ([Webpage](https://www.techscience.com/cmc/v70n2/44641))

# Database 
[Ham10000 database](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/DBW86T/GQGSWO&version=2.0)

[ISIC 2019 database](https://challenge2019.isic-archive.com/data.html)
