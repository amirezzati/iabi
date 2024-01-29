# Project details

All notebooks that I had implemented in this course are listed below.     
You can access them by clicking on their title

## [Classic methods](https://github.com/amirezzati/iabi/blob/main/homeworks/HW1/pract/Classic_HW.ipynb)
In this notebook, I implemented some classic methods in denoising, enhancement, and sharpening the CT-scan images.   

## [Brain MRI classification](https://github.com/amirezzati/iabi/blob/main/homeworks/HW1/pract/Brain_MRI_Classification_HW.ipynb)
In this notebook, I used Pytorch ResNet model to predict which brain MRI image has tumor or not. Subsequently I reported some metrics and visualized feature space with TSNE.

## [Brain MRI Classififcation with AlexNet](https://github.com/amirezzati/iabi/blob/main/homeworks/HW2/pract/Brain_MRI_Classification_with_AlexNet.ipynb)
In this notebook, I implemented AlexNet model from scratch to classify brain MRI images into three different classes. Subsequently I separately trained encoder section with Supervised Contrastive loss and also trained classifier section with Cross Entropy loss.

## [CellProfiler](https://github.com/amirezzati/iabi/tree/main/homeworks/HW3/pract-solution)
In this project, I used CellProfiler tool and implemented a pipeline to automate the process of biological objects analysis.
<p align="center">
<img src="https://github.com/amirezzati/iabi/assets/62298323/3f44827f-c721-46ec-9863-cf1a0754f8bd" height="300">
<img src="https://github.com/amirezzati/iabi/assets/62298323/38bfa3b6-985f-4786-8410-ea30428bd9a2" height="300">
</p>

## [Image Registration](https://github.com/amirezzati/iabi/blob/main/homeworks/HW4/pract/HW4_Image_Registration.ipynb)
In this notebook, I implemented VoxelMorph from scratch to register retinal pairs.      
VoxelMorph, an established approach in this field, utilizes deep learning and the U-Net architecture for streamlined image registration. It accurately aligns images by learning deformations, making it advantageous for complex spatial relationships and detailed feature preservation in medical image analysis.
<p align="center">
<img src="https://github.com/amirezzati/iabi/assets/62298323/18dbf09c-7455-4507-8dd9-8b3bdebb4fa0" height="300">
</p>

## [Multiple Instance Learning](https://github.com/amirezzati/iabi/blob/main/homeworks/HW4/pract/HW4_MIL.ipynb)
In this notebook, I implemented the idea proposed by the paper "Breast Cancer Histopathology Image Classification and Localization using Multiple Instance Learning" and reproduced some of their results.

## [Graph Neural Network](https://github.com/amirezzati/iabi/blob/main/homeworks/HW4/pract/HW4_GNN.ipynb)
In this notebook, I implemented three different sections:
1. Nuclei extraction
  <p align="center">
  <img src="https://github.com/amirezzati/iabi/assets/62298323/de05a1cd-096f-43fe-a0bb-a16f20fc577a" height="300">
  </p>                  

2. Graph convolutional network     
   I implemented a GCN model to generate node embeddings of graph.       
3. Graph prediction model                     
   I implemented a GCN Graph Prediction model using the node embeddings from the GCN model and global pooling to create graph-level embeddings.
- This figure provides an architecture overview of sections 2 and 3:           
   <p align="center">
    <img src="https://github.com/amirezzati/iabi/assets/62298323/f1a2f27e-2a73-475a-8acd-73b8fce9f50f">
   </p>    

## [Interpretability](https://github.com/amirezzati/iabi/blob/main/homeworks/HW5/pract/HW5_Interpretability.ipynb)       
In this notebook, I used Grad-CAM technique as an interpretability algorithm that aids in comprehending the model's decision-making process, debugging, and explaining predictions to non-technical stakeholders. I visualized attention maps over CT-scan images to find out ResNet model focus on which features for classification.       
<p align="center">
  <img src="https://github.com/amirezzati/iabi/assets/62298323/c1b30682-f443-4bf8-afc2-8d034552f39d" height="250">
</p>   

## [Classification using Swin Transformer](https://github.com/amirezzati/iabi/blob/main/homeworks/HW5/pract/HW5_BreastMNIST_Classification.ipynb)       
This task involves using the Swin Transformer, a cutting-edge neural network model, to distinguish between benign (including normal) and malignant cases in BreastMNIST dataset. There is a common challenge of class imbalance in this task, and I used weighted BCE loss to overcome this problem and improve the model.        
<p align="center">
  <img src="https://github.com/amirezzati/iabi/assets/62298323/1627f0cc-4f63-4fa6-8f04-029f1bc3396a" height="400">
</p>  

## [2D and 3D Segmentation](https://github.com/amirezzati/iabi/blob/main/homeworks/HW5/pract/Segmentation/HW5_Segmentation.ipynb)
In this notebook, I implemented both 2D-UNet and 3D-UNet models to perform segmentation on a set of 30 volumetric medical images.         
<p align="center">
  <img src="https://github.com/amirezzati/iabi/assets/62298323/c268c596-bc9b-4348-9965-d48099b2df2f" height="600">
</p>   

</br>      
<hr>       

**Details of other projects will be posted soon...**
