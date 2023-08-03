# EICL-Net  
This is a pytorch implementation of EICL-Net.  
# Environment  
* pytorch==1.3.1
* cuda 10.1  
* python==3.7  
* opencv 4.4.0.46  
* libtiff 0.4.2  
# Data Preparation  
1. Please prepare multisource data panchromantic, multispectral images and label file.  
2. The image file format is ".tif" or ".tiff".  
3. The label file format is ".mat" or ".npy".  
# Train  
If you want to train your own dataset:  
1. Put your own dataset and label file to 'EICL-Net/Image/'.  
2. Run 'python Train_EICL-Net.py'.  
3. Save model like 'EICL-Net/Models/1.pkl'.  
# Performance Evaluation  
If you want to evaluate the performance of model:  
1. cd EICL-Net/Test_EICL-Net.py  
2. python Test_EICL-Net.py  
# Visualize  
If you want to visualize the experimental result:  
1. cd EICL-Net/Color.py  
2. python Color.py  
