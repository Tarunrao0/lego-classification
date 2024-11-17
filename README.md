
<p align="center">
    <img src="https://github.com/user-attachments/assets/da0109b9-1aa6-447b-9cf5-9d4fd4a992ff" alt="lego banner" height="200">
</p>

# Lego Brick Classification with CNN

This project features a **Convolutional Neural Network (CNN)** that classifies LEGO bricks into **16 different categories**. The model is designed to facilitate applications in **automated sorting** and **inventory management**, making it easier for users to organize and utilize their LEGO collections effectively. By leveraging advanced image recognition techniques, this CNN not only enhances the sorting process but also opens up possibilities for more efficient inventory tracking and management in various contexts.

## Kaggle Dataset 
[Images of LEGO Bricks](https://www.kaggle.com/datasets/joosthazelzet/lego-brick-images)

A dataset containing 12,700 images of different lego bricks divided into 16 categories, each category containing 400 images

## Approach

- Normalized the images to have pixel values in the range[0, 1]
- Built a CNN with 4 convolutional layers, followed by pooling and dense layers
- Implemented Dropout layers to reduce overfitting

## Performance

- **Accuracy** : 95.0%
- **Precision** : 100.0%
- **Recall** : 99.8%

## Test Image Results

![Screenshot 2024-11-10 010230](https://github.com/user-attachments/assets/8b9aa16d-eadd-4465-ba38-264e24dc0f23)
![Screenshot 2024-11-10 013557](https://github.com/user-attachments/assets/ca5dff78-3021-4ad7-831c-a6190ccf0833)

# Links 🔗:
**Kaggle Dataset** : [Images of LEGO Bricks](https://www.kaggle.com/datasets/joosthazelzet/lego-brick-images) \
**Model with 95% accuracy** : [legos 95](https://drive.google.com/file/d/13LuV9sVNeApDJOtcoOrnc-8SDCnHwge_/view?usp=sharing)
