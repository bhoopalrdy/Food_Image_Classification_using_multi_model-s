# Food_Image_Classification_using_multi_model-s
Objective:The main goal of this project is to classify food items by uploading their images. This deep learning-based food classification model leverages multiple architectures to categorize 34 different food types. The project encompasses data collection, dataset balancing, model training, validation, and deployment using Flask
# 1.DATA COLLECTION
- We are working on a food classification project, so we sourced images for a high-quality dataset from Kaggle that includes 34 different food categories. We also need this dataset to properly train a deep learning model.
- It includes a diverse range of food items to improve model accuracy and generalization.

- You can download the dataset from the following link:
- [Food_Classification](https://www.kaggle.com/datasets/harishkumardatalab/food-image-classification-dataset)

![FCD_TASK1_IMAGE](https://github.com/user-attachments/assets/ceae8a62-3069-46b2-a6a7-6d935ca3849a)
# 2.DATA BALANCING
- To improve model performance and ensure fair representation, data balancing techniques are applied, making the dataset evenly distributed across all 34 food categories.
- We use Python scripts to balance the dataset, ensuring each class contains exactly 200 images.
- The dataset is then split into three subsets:
    - Training Set: 150 images per class
    - Validation Set: 30 images per class
    - Testing Set: 20 images per class
- Finally, the balanced dataset is uploaded to Google Drive for easy access and further processing.
# 3.Development Environment & Library Imports:
- We use Google Colaboratory for this project due to its free access to GPU, which significantly enhances deep learning model training compared to a CPU.
- After uploading the dataset to Google Drive, a new Colab notebook is created to begin coding.
- The first step is to mount Google Drive to access the dataset.
- Next, we import the necessary libraries, each serving a specific purpose:
  
Importing Required Libraries:
