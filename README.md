![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

# CNN with Early exit

This Repository refers to the Final Project of the course [Neural Networks for Data Science (NNDS)](https://www.sscardapane.it/teaching/nnds-2022/) at University Sapienza of Rome 2022/2023.

## Abstract
<div style="text-align:center">
 <p align="center">
  <img src='img/leaf.png'/>
  
  </p>
  <p align="center">
  </p>
</div>
## Dataset

The dataset chosen for this homework is [**Corn and Maize Leaf Disease Dataset**](https://www.kaggle.com/datasets/smaranjitghose/corn-or-maize-leaf-disease-dataset) from kaggle. The authors of this dataset created it using the PlantVillage and PlantDoc datasets. In this dataset we have 4188 images divided into four classes, representing some of the different states the plant leaf can be in:

* Common Rust - 1306 images
* Gray Leaf Spot - 574 images
* Blight -1146 images
* Healthy - 1162 images


The idea of using this dataset stems from my interest in plants. Moreover, maize being a plant used all over the world, the ability to recognise diseases promptly can avoid unpleasant scenarios.

The task is Image Classification.

Since my dataset is not stored separately in train/validation/test i did it myself. I divided the data as follows:

*   70% train set
*   15% validation set
*   15% test set

