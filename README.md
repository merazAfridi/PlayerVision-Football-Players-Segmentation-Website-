## PlayerVisionSegmentationGradCAM

This project uses computer vision to find and highlight football players in pictures. It uses a method called Grad-CAM to show how the computer makes its decisions. The goal is to help understand player actions and performance better by making the computer's decisions easy to see.
#### Homepage
![Homepage](https://github.com/merazAfridi/PlayerVision-Football-Players-Segmentation-Website-/blob/main/homepage%20demo.PNG)
#### Result
![Results](https://github.com/merazAfridi/PlayerVision-Football-Players-Segmentation-Website-/blob/main/Result%20Page%20demo.PNG)
#### About Me
![About Me](https://github.com/merazAfridi/PlayerVision-Football-Players-Segmentation-Website-/blob/main/about%20me%20page%20demo.PNG)

### Dataset Description

This project utilizes two datasets related to football player segmentation for computer vision tasks:

---

1. [Football Player Segmentation Dataset](https://www.kaggle.com/datasets/ihelon/football-player-segmentation)

   This dataset contains images of football players in various playing positions, such as goalkeepers, defenders, midfielders, and forwards. The images are captured from different angles and distances. Each image is annotated with pixel-level masks that specify player locations and segmentation boundaries.



   **Use Cases:**  
   - Player detection and segmentation during matches.  
   - Analyzing player movements and behaviors.  
   - Exploring performance metrics and trends based on positional data.
     
![Dataset Image](https://github.com/merazAfridi/PlayerVision-Football-Players-Segmentation-Website-/blob/main/static/results/f1ed0910592644f3b0cb340f41ee6d9c_resized.png)

---

2. [Football Players Masks for Image Segmentation Dataset](https://www.kaggle.com/datasets/drmwnnrafi/football-players-masks-for-image-segmentation)

   This dataset, derived from the ⚽ Football Players Segmentation ⚽ dataset by Yaroslav Isaienkov, converts the annotations from COCO JSON format to JPG format. The dataset includes images of 512 x 512 dimensions. The complete dataset, including original images and annotations, can be accessed via the provided link.

---
#### Image, Predicted MASK & GradCAM Analysis
![Dataset Image Prediction](https://github.com/merazAfridi/PlayerVision-Football-Players-Segmentation-Website-/blob/main/evaluation.png)

---


### Attribution

I extend my gratitude to:  
- [ihelon](https://www.kaggle.com/ihelon) for providing the **Football Player Segmentation Dataset**.  
- [DrMwNNRafi](https://www.kaggle.com/drmwnnrafi) for creating the **Football Players Masks for Image Segmentation Dataset**, which is based on the dataset by Yaroslav Isaienkov.



Please refer to the respective links for detailed licensing and usage terms provided by the authors.

