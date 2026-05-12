# Medical Image Segmentation using U-Net with ResNet18 Backbone

#### 📌 Goal

The goal of this project was to develop a deep learning-based medical image segmentation model to identify and segment jaw regions using U-Net architecture with a ResNet18 backbone. This project  explored semantic segmentation techniques for medical imaging and evaluate segmentation performance using IoU metrics.

---

#### 🔬 Methodology

1. Processed a paired medical image dataset consisting of jaw images and corresponding segmentation masks
2. Implemented U-Net architecture with ResNet18 as the encoder/backbone for feature extraction
3. Performed image-mask preprocessing and dataset splitting into training, validation, and testing sets
4. Trained the segmentation model using deep learning techniques
5. Evaluated model performance using segmentation accuracy and Intersection over Union (IoU)

---

#### 📊 Results

Train and Validation Loss Plot

![Train and Validation Loss Plot](https://github.com/floweredscent/image-segmentation-unet/blob/main/results/Train%20and%20Validation%20Loss%20Plot.png)

Train and Validation Dice Score Plot

![Train and Validation Dice Score Plot](https://github.com/floweredscent/image-segmentation-unet/blob/main/results/Train%20and%20Validation%20Dice%20Score%20Plot.png)


- Training and validation loss decreased consistently across epochs, with final validation loss reached approximately 0.39. This indicates a successful model learning.
- Training and validation Dice Scores increased steadily throughout training.
- Final validation Dice score reached approximately 0.82, indicating good segmentation overlap.
- The Intersection over Union (IoU) value obtained was 0.3916. A  higher IoU value indicates better alignment between the predicted region and the actual region, which indicates a more accurate model.
- Overall, the model demonstrated effective performance for medical image segmentation tasks.

---

#### 📁 Output Visualizations


![Example of The Segmentation Results.](https://github.com/floweredscent/image-segmentation-unet/blob/main/results/Example%20of%20Segmentation%20Result.png)

Example of The Segmentation Result.
