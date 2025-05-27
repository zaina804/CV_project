## Computer Vision Project
3D Object Recognition using Graph Neural Networks (GCNs)

## Overview
This project focuses on classifying **3D objects** from the **ModelNet10** dataset using **Graph Convolutional Networks (GCNs)**.  
We work with **point cloud data** and apply geometric deep learning to recognize object shapes from multiple categories.

## Tools & Technologies
- Python
- PyTorch Geometric
- GCN (Graph Convolutional Networks)
- ModelNet10 Dataset
- Matplotlib (3D Visualization)
- Scikit-learn (Evaluation Metrics)

## Dataset
ModelNet10 is a benchmark dataset containing 3D CAD models from 10 object classes.  
In this project, we:
- Sample 1024 points from each object
- Normalize and augment point clouds
- Visualize each object using 3D scatter plots

## Project Features
- ✅ Load and process ModelNet10 with `SamplePoints`
- ✅ Train GCN on graph-represented point cloud data
- ✅ Visualize sample point clouds in 3D
- ✅ Evaluate model using classification report and confusion matrix
- ✅ Export generated 3D object plots as PNG images

## Sample Output

Example visualization of a `monitor` object from the dataset:

![image](https://github.com/user-attachments/assets/0740f3d7-ae3f-4008-8716-ddf62988d886)


Images are saved to `/output_shapes` during runtime.


Getting Started

## Installation
```bash
pip install torch torchvision torch-geometric matplotlib 
```

## Run the Project
```bash
jupyter notebook CV_PROJECT.ipynb
```

## About Me
Hi! I’m **Zaina Laham**, a Data Science & AI student passionate about:
- Machine Learning
- OpenCv
- Natural Language Processing
- Deep Learning
- Python
- Data Science

📬 Let’s connect on [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/zaina-laham-b6807530b)
