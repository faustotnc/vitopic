# ViTopic: Topic Modeling on Images with Clustering of Vision Transformer Embeddings

Image data plays a critical role in many fields such as social media analysis, medical imaging, and marketing. However, collecting, sorting, clustering, and labeling large amounts of image data can be a challenging and time-consuming task that often requires significant human resources. The proposed work aims to develop an automated system that can cluster and describe large datasets of unlabeled images, allowing analysts to quickly and accurately process vast amounts of visual data. This project's primary objective is to create a tool that can help people automatically cluster images into groups and generate text-based topics for each cluster, which will help them extract meaningful insights from the data. By automating this process, the system will significantly improve image data processing efficiency, reduce labor costs, and facilitate the analysis of visual data.

![Main Idea](./docs/main-idea-dark-mode.png#gh-dark-mode-only)
![Main Idea](./docs/main-idea-light-mode.png#gh-light-mode-only)

## How It Works
Below are the general steps to generate context-guided visual topics:
1. Generate vision embeddings and image captions using pre-trained models.
2. Generate a pair-wise similarity matrix using the vision embeddings and some similarity function. This matrix can be used for visual similarity search.
3. Assign clusters to the vision embeddings using a clustering algorithm.
4. Use the cluster information and the image captions to generate a Class-based Term-Frequency Inverse-Document-Frequency (c-TF-IDF) matrix.
5. Extract frequent words in each cluster from the c-TF-IDF matrix.

![Main Idea](./docs/model-pipeline-dark-mode.png#gh-dark-mode-only)
![Main Idea](./docs/model-pipeline-light-mode.png#gh-light-mode-only)

## Installing & Running
```
Coming Soon...
```

---
Final Project for ITCS-5156 @ UNC Charlotte
