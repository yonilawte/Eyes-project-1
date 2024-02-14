# Automated Diabetic Retinopathy Detection

The Automated Diabetic Retinopathy Detection project aims to address the challenges associated with manual interpretation of retinal images for Diabetic Retinopathy screening by developing an automated tool. This tool utilizes deep learning techniques to accurately detect and grade Diabetic Retinopathy, thereby enabling early intervention and personalized treatment plans.



## Data Description

The dataset comprises a large collection of high-resolution retinal images captured under various imaging conditions. Each image has been assessed by a medical professional for the presence of Diabetic Retinopathy and assigned a rating on a scale ranging between 0 and 1. The ratings correspond to the following categories:
- Diabetic Retinopathy: 0
- No Diabetic Retinopathy: 1
## Approach
- **Model Architecture:** The project utilizes the VGG16 model with a custom classifier tailored for Diabetic Retinopathy detection.
- **Evaluation Metrics:** The performance of the model is assessed using a confusion matrix to measure classification accuracy and identify any misclassifications.
- **Visualization:** The results are visualized using Plotly, showcasing sample images along with their predicted labels, loss, accuracy, and other relevant metrics.
## Framework
- **PyTorch:** PyTorch is used for building and training the deep learning model.
- **Torchvision:** Torchvision is leveraged for accessing pre-trained VGG16 model and other utilities.
- **Plotly:** Plotly is utilized for visualizing the results, including images, metrics, and confusion matrix.
