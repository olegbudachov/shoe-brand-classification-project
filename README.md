# Shoe Brand Classification | Multiclass Classification using Transfer Learning
## Project steps:
1. Primary goal of the project
2. Data overview
3. Data preprocessing and EDA
4. Model building
5. Model training
6. Model evaluation and tuning
7. Model testing
8. Conclusion
9. References
    
## 1. Primary goal of the project
The primary goal of this project is to employ transfer learning with the InceptionV3 model, a deep convolutional neural network (CNN) architecture developed by Google's research team, which is primarily designed for image classification and object recognition tasks. Our objective is to use this powerful architecture to categorize images of shoes into three distinct brands: Nike, Adidas, and Converse.

## 2. Data overview
add Codeadd Markdown
The dataset is structured into two folders, one for test data and the other for training data, with a test-train-split ratio of 0.14. The test dataset comprises 114 images, while the training dataset consists of 711 images. All images are in RGB color format and have a resolution of 240x240 pixels. Within both folders, there are three distinct classes: Adidas, Converse, and Nike. This dataset was acquired by downloading images from Google Images. Images in .webp format were converted to .jpg format. Subsequently, the images were randomly shuffled and resized to ensure a consistent resolution of 240x240 pixels for all samples.
