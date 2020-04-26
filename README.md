# COVID-19
### Automated Detection of COVID-19 Cases Using Deep Neural Networks with X-Ray Images

In this project, a deep learning [model](https://github.com/muhammedtalo/COVID-19/blob/master/DarkCovidNet.ipynb) is proposed for the automatic diagnosis of COVID-19. The proposed [model](https://github.com/muhammedtalo/COVID-19/blob/master/DarkCovidNet.ipynb) is developed to provide accurate diagnostics for binary classification (COVID vs. No-Findings) and multi-class classification (COVID vs. No-Findings vs. Pneumonia). Our [model](https://github.com/muhammedtalo/COVID-19/blob/master/DarkCovidNet.ipynb) produced a classification accuracy of 98.08% for binary classes and 87.02% for multi-class cases. The  [DarkNet model](https://github.com/muhammedtalo/COVID-19/blob/master/DarkCovidNet.ipynb) was used in our study as a classifier for the you only look once (YOLO) real time object detection system. We implemented 17 convolutional layers and introduced different filtering on each layer.  
##### X-ray Image [DataSet](https://github.com/muhammedtalo/COVID-19/tree/master/X-Ray%20Image%20DataSet/)

X-ray images obtained from two different sources were used for the diagnosis of COVID-19. A COVID-19 X-ray image [database](https://github.com/ieee8023/COVID-chestxray-dataset/)  was developed by Cohen JP using images from various open access sources. This database is constantly updated with images shared by researchers from different regions. There are 43 female and 82 male cases in the database that were found to be positive. In this dataset, a complete metadata is not provided for all patients. Also, the ChestX-ray8 [database](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community) provided by Wang et al. was used for normal and pneumonia images. In order to avoid the unbalanced data problem, we used 500 no-findings and 500 pneumonia class frontal chest X-ray images randomly from this database. 

 ## Citation
 
 ##### The paper is avaible [here](https://www.researchgate.net/publication/340935440_Automated_Detection_of_COVID-19_Cases_Using_Deep_Neural_Networks_with_X-ray_Images).
 

