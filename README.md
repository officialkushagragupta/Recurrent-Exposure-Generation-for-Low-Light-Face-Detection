# Recurrent Exposure Generation for Low Light Face Detection

## Introduction
**Problem Statement:** Face detection in low-light conditions presents significant challenges due to limited photon availability, inherent noise, and uneven distribution of light. These factors complicate the detection of small, blurred, and partially occluded faces, which are crucial for applications in security and mobile technology.

**Objective**: The project aims to enhance the accuracy and reliability of face detection under low-light conditions through innovative image enhancement techniques.

![image](https://github.com/officialkushagragupta/Recurrent-Exposure-Generation-for-Low-Light-Face-Detection/assets/96885711/cc88263b-8dec-4c50-8770-64a0671a2779)


# Proposed Method

**ZeroDCE-Net Improvement:**

The modified ZeroDCE-Net method developed for this project enhances low-light images by ensuring that the color integrity of the images is maintained. This approach shows a significant improvement in preserving details in low-resolution faces when compared to other methods, as tested on the DARK FACE dataset.
![image](https://github.com/officialkushagragupta/Recurrent-Exposure-Generation-for-Low-Light-Face-Detection/assets/96885711/5147a83b-b4e2-4fdb-af85-a20764cfbde6)

**Multi-Exposure Simulation:**

This project simulates the effects of multi-exposure photography from a single image to improve the quality of the images. Although replicating the effects of multiple exposures from a single image is complex, the integration of this technique helps to enhance the image details significantly before face detection.
![image](https://github.com/officialkushagragupta/Recurrent-Exposure-Generation-for-Low-Light-Face-Detection/assets/96885711/9ea41511-b30c-4970-8527-45f4fa330afb)

## System Architecture
![image](https://github.com/officialkushagragupta/Recurrent-Exposure-Generation-for-Low-Light-Face-Detection/assets/96885711/e73747b7-8b30-4a0e-8d44-10cb5be3f2a3)


## Implementation

**Face Detection Model:** Utilizes the DCE-NET model, specifically tailored to handle low-light images enhanced through our developed techniques.

**DNN Algorithm:** A Deep Neural Network (DNN) is employed to detect faces after the images have been enhanced. This step is crucial for assessing the effectiveness of the enhancements.

**Dataset and Testing:**
The Dark Face dataset is used to evaluate the performance.
The testing protocols are designed to measure improvements in detection accuracy and detail preservation under low-light conditions.

# Results and Evaluation

![image](https://github.com/officialkushagragupta/Recurrent-Exposure-Generation-for-Low-Light-Face-Detection/assets/96885711/76ff4e03-2e65-4511-8f59-494f356f3ae9)

**The model demonstrated remarkable improvements throughout the training:**
 
 The total loss was reduced by approximately **92.30%.**
 
 The validation total loss was reduced by about **90.96%.**


