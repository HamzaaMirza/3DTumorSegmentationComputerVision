# 3DTumorSegmentationComputerVision
Person Project in which I try and design a 3D U-Net model that is used to train on 3D MRI Scans of Brain and is used to predict the presence of a Tumor. This project is an extension of my previous project in which I did the exact same thing but on 2D segments and this is an extension of that project in 3D

CHALLENGES FACED: 
1. I had to learn how to clean and pre process the 3D data.
2. Since the 3D data is hard and computationally heavy to process I had to create:
                a. Preprocessing data pipeline
                b. Data loader (to not use all the available ram at the same time)
 
4. The main problem is that even after doing all this, the model and the computation was so big that it would take around 50 hours to train the model in 50 epochs and I had not upgraded the volab plan to pro
5. So, the model that I have right now is trained only on 2 epochs and
NOTE: Any one can take this architecture and train the model on their machine,
 
