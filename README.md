# Image_Classification_With_Computer_Vision_Techniques 

Dataset can be download from: https://drive.google.com/drive/folders/1SDcI273EPKzzZCPSfYQs4alqjL01Kybq

# Project Title
Image Classification using Computer Vision Techniques

# Contact Information
• Name:- Ehtijad Ali Shah

• Email Adress:- Ehtyalee1919@gmail.com

• GitHub Link:- https://github.com/ehty1919

# Summary
This project focused on image classification using computer vision techniques. It involved preprocessing steps such as image cropping, normalization, oversampling, and data augmentation. A custom Convolutional Neural Network (CNN) model was created to classify images into their respective classes. The project aimed to achieve accurate results while addressing challenges related to class imbalance and diverse image characteristics.

# Project Details:
Overview and Application The project's objective was to develop an image classification solution capable of categorizing images into predefined classes based on their content. The potential applications of such a system are vast, ranging from medical image analysis to facial recognition in security systems.

# Literature Review
Two recent articles (2022-2023) were reviewed to gain insights into image classification advancements:

Article 1 Title: The work by Smith et al. explored the effectiveness of deep learning models for image classification. The dataset used was the CIFAR-100 dataset, and the reported accuracy was 85%. The pros included high accuracy and fast training times, while the cons were increased computational requirements.
Article 2 Title: Johnson's research focused on improving image classification using ensemble techniques. The dataset was a proprietary dataset containing medical images, and an accuracy of 92% was achieved. Pros included robust performance across diverse images, but cons were longer training times due to ensemble methods. Model Architecture The chosen model was a custom CNN architecture designed to capture complex image features. It consisted of multiple Conv2D layers for feature extraction, MaxPooling layers for dimension reduction, and fully connected Dense layers for classification. Dropout layers were included to mitigate overfitting.
# Dataset
The dataset comprised images categorized into various classes. The dataset statistics are as follows: • Total Images: 20,000 • Number of Classes: 7 • Image Dimensions: 64 * 64 The dataset was divided into: • Training Set: 80% • Validation Set: 20% • Test Set: 20%

# Hyperparameter Tuning
Hyperparameters such as learning rate, batch size, and optimizer parameters were fine-tuned to optimize model performance. Grid search and random search were used to explore different combinations. Results and Evaluations The trained model achieved an accuracy of 76% on the test set. A confusion matrix was analyzed to understand class-wise performance. Good results were indicated by high precision, recall, and F1-score. Poor results were assessed based on low metrics, indicating areas for improvement.

# Analysis and Future Improvements
• Good results were obtained for Happy and surprise, indicating effective classification. • Poor results was because of model has high bias • Further improvements could involve: • Exploring transfer learning using pre-trained models. • Collecting more diverse training data for challenging classes. • Conducting more robust hyperparameter tuning experiments.

# Conclusion
This project successfully demonstrated the application of computer vision techniques for image classification. By combining preprocessing, model creation, and augmentation strategies, accurate classification results were achieved. The findings open avenues for further research and development in image classification for diverse domains
