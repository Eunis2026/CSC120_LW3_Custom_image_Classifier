# CSC120_LW3_Custom_image_Classifier
This is the Link for the Google Colab:  https://colab.research.google.com/drive/1xzCEOLH0TJKoC6skdJa2VmsEgbrhx3e8?usp=sharing

Guide Questions (Student Reflection & Explanation)

1. Dataset Preparation
   
○ How did you organize your dataset in Google Drive?

Ans:I organized my dataset in Google Drive by creating a structured folder system to keep all files clean and easy to access.

MyDrive/
└── ImageDataset/
├── ClassA/
│ ├── img1.jpg
│ ├── img2.jpg
├── ClassB/
│ ├── img1.jpg
│ ├── img2.jpg
├── ClassC/

○ Why is folder structure important for TensorFlow image loading?

Ans: Folder structure is important because it makes everything simpler and automatic when working with TensorFlow.

2. Model Training
   
○ What is the role of convolutional layers in image classification?

Ans: Convolutional layers are the part of the model that helps it “see” and understand images when using TensorFlow.

○ Why do we split data into training and validation sets?

Ans: We split the data so we can train the model and also check if it’s actually learning properly when using TensorFlow.

3. Performance Analysis
   
○ What accuracy did your model achieve?

Ans: In my dataset, I had 250 images per class, which is a moderate amount of data. This helped the model learn the basic patterns of each class. The training accuracy reached around 99%, but the validation accuracy was lower at about 72%, which suggests that the model may have slightly overfitted the training data.

○ How did the number of images affect the model’s performance?

Ans: When there were more images, the model performed better because it had more examples to learn from. This helped it recognize patterns more accurately and improved its overall accuracy.

4. Critical Thinking
   
○ What challenges did you encounter while using your own dataset?

Ans: There were some technical challenges, like setting up the dataset correctly in Google Drive and making sure it loaded properly in the training environment.

○ How can data augmentation improve your model?

Ans: Data augmentation helps improve the model by creating more variety in the training data without needing to collect new images, especially when using TensorFlow.

5. Application:
   
○ Suggest a real-world application for your trained model.

Ans: A real-world application of my trained model using TensorFlow could be an image-based classification system, such as a plant disease detection app or a product sorting system.

○ How can this system be integrated into a mobile or web application? 

Ans: The trained model using TensorFlow can be integrated into a mobile or web application by turning it into a service that the app can use for predictions.

**Guide Questions** 

Visualization & Overfitting:

1. What signs indicated overfitting in your first model?
   Ans: Training accuracy keeps increasing, but validation accuracy plateaus
   
Training accuracy goes up to ~99%

Validation accuracy stops around ~73% and doesn’t improve much

2. How did data augmentation affect validation accuracy?
   Ans:It increased steadily at the start (from ~0.30 → ~0.70+)
   
Model Improvement

3. What is the purpose of dropout layers?
   
   Ans: Dropout is a regularization technique used to prevent overfitting in neural networks
   
4. Why does data augmentation improve generalization?
   Ans: it’s like teaching someone using examples from different angles and situations—so when they see something new, they can still recognize it.
   
Performance Comparison:

5. Compare accuracy before and after improvements.
    Ans:
    Before: High accuracy but poor generalization (overfitting)

    After: Balanced accuracy and better real-world performance
   
6. Which technique contributed most to improvement?
   Ans: Data Augmentation
   

Deployment & Application:

7. Why is saving the model important?
   ANS: Saving your model is important because it lets you keep all the learning your model has done so you don’t have to train it again from scratch.

9. How can this model be deployed in a real-world system?
After training and saving your model, deployment means making it usable by other people or systems.
