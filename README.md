# Google-Image-V5
DATA 603 Final Project

For this project, our team set out to compare the image labels between the Google Image Dataset
V5 and a pre-trained convolutional neural network model - ResNet50. Utilizing the University of
Maryland - Baltimore County’s Big Data Cluster, our team was able to leverage the Hadoop Distributed
File System to carry out this project. After initial exploratory data analysis, we realized the differences in
labels between the Google Image Dataset V5 and ResNet50. This shifted the team’s data subset focus
from human body parts to reptiles. Having chosen reptiles as our data subset within the Google Image
Dataset V5, our analysis showed that ResNet50 goes a layer deeper than the Google Image Dataset V5
(snakes, crocodiles, lizards, but not dinosaurs). The findings were further validated after adjusting the
confidence levels from 0 to 1 for the image labels. All analysis and findings can be found in the
accompanying Jupyter Notebook.
