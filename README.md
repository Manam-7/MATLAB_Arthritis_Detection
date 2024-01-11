# MATLAB_Arthritis_Detection
Welcome to the repository for "Determination and Analysis of Arthritis using MATLAB Techniques"! 

This repository offers a comprehensive framework for analyzing and detecting arthritis in medical images using MATLAB.

## INTRODUCTION:

This project aims to develop a framework for analyzing and detecting arthritis in medical images using MATLAB. Early and accurate diagnosis of arthritis is crucial for effective treatment and improving patient outcomes. Our framework leverages image processing and machine learning techniques to provide valuable insights into joint health, potentially leading to earlier diagnoses, personalized treatment plans, and reduced reliance on invasive procedures.

## PROBLEM STATEMENT:

Arthritis is a prevalent and debilitating condition affecting millions worldwide. Traditional diagnosis methods often rely on X-rays and physical examinations, which can be subjective and limited in their ability to detect early-stage arthritis. This can lead to delays in treatment and worsen long-term outcomes. Additionally, invasive procedures like joint biopsies are sometimes required for definitive diagnosis, posing risks and discomfort to patients.

## SYSTEM DESIGNS AND FLOWCHART:

Our framework consists of four main modules:
1. Image Preprocessing: Enhances image quality by removing noise, smoothing, and adjusting contrast.
2. Segmentation Techniques: Isolates joint regions and identifies cartilage for further analysis.
3. Feature Extraction: Extracts relevant features from segmented images, such as cartilage thickness, texture, and shape.
4. Machine Learning Models: Implements models for:
    - Classification: Identifying the presence or type of arthritis.
    - Progression Prediction: Predicting the future course of the disease.
    - Treatment Response: Assessing how a patient might respond to different treatments.
### Flowchart:

<img width="189" alt="image" src="https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/e3077c7d-0efb-43da-95f0-77ddb51e6bb2">

	This flowchart outlines the process of our MATLAB framework for analyzing and detecting arthritis in medical images. It starts with the input image, followed by selecting control points to define key anatomical landmarks. These points guide the B-spline curve fitting, which smooths the image while preserving crucial details like cartilage edges. Next, anisotropic diffusion further refines the image by selectively blurring noise while keeping important features sharp. Canny and LoG edge detection algorithms then precisely identify joint boundaries and subtle intensity changes, respectively, both of which are crucial for arthritis diagnosis. Finally, cartilage thickness is measured, and normal/abnormal tissue is classified based on predefined thresholds. This entire process is repeated for multiple images to provide a comprehensive analysis of joint health and potential arthritis progression.

## PROJECT SCREENSHOTS:

![image](https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/44169074-91cf-4373-89d8-875e74d0fd74)
![image](https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/52012625-50f0-48eb-a31e-997712d76f40)

	The first step in this process is to select the control points.

![image](https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/1fb83765-4252-42d9-bcdd-12a5b2b59946)

	Anisotropic diffusion in this project acts like a smart filter for medical images! Unlike blurring everything, it smooths noise while preserving edges and fine details (like cartilage borders) crucial for arthritis diagnosis. Think of it as selectively blurring the "background" of the image, letting important features stand out!

![image](https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/bcee3173-1669-488a-a90b-78eb1a938fbb)

	Canny edge detection precisely pinpoints the boundaries of joint structures in medical images. These sharp, accurate edges become crucial inputs for subsequent analyses, like measuring cartilage thickness or analyzing bone shape, which are essential for diagnosing and monitoring arthritis.

![image](https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/909986fe-7dac-49bc-a0dd-07501bb913b0)

	Log edge detection, in this project, highlights subtle changes in brightness that often signal cartilage thinning or bone erosion, early signs of arthritis. This technique helps identify these subtle changes even in noisy medical images, enabling earlier detection and intervention.

![image](https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/cfede3d3-a36b-4cba-913c-58ca9a3a2f60)

	Control point adjustment in this project acts like a fine-tuning tool for medical images. It allows researchers to precisely manipulate curves and surfaces representing joint structures, ensuring accurate alignment and measurements for arthritis analysis. Think of it like adjusting the  "skeleton" of the image to make sure it perfectly matches the actual anatomy, leading to more reliable results.

![image](https://github.com/Manam-7/MATLAB_Arthritis_Detection/assets/155944488/95f7e3bb-345d-4c38-bafd-e1ba888de485)

	The output image shows a thickness of 3.52822, classified as abnormal, likely indicating the presence of arthritis based on the predefined thresholds used in the project.

## SPECIFICATIONS:

### Software:
    Matlab 2018a or above
### Hardware:
#### Operating Systems:
      Windows 10
      Windows 7 Service Pack 1
      Windows Server 2019
      Windows Server 2016
#### Processors:
      Minimum: Any Intel or AMD x86-64 processor
      Recommended: Any Intel or AMD x86-64 processor with four logical cores and AVX2 instruction set support
#### Disk:
      Minimum: 2.9 GB of HDD space for MATLAB only, 5-8 GB for a typical installation
      Recommended: An SSD is recommended A full installation of all MathWorks products may take up to 29 GB of disk space
#### RAM:
      Minimum: 4 GB
      Recommended: 8 GB
      
# Conclusion: 

This project represents a significant step towards utilizing advanced image analysis and machine learning for arthritis diagnosis and management. By fostering further development and collaboration, we can hope to improve patient outcomes and contribute to a healthier future.

## Documentaion:
- [Project Ppt] (https://github.com/Manam-7/MATLAB_Arthritis_Detection/blob/45e7924c1cb2cf8fbaa3b5b6f0d69819333deb09/Final%20PPT.pptx)
- [Final Report]

## References:

 - https://www.mathworks.com/help/images/medical-image-processing-app.html
 - https://www.mathworks.com/help/images/image-processing-learning-resources.html
 - https://www.amazon.com/Digital-Image-Processing-3rd-Gonzalez/dp/013168728X
 - https://www.cambridge.org/core/books/matlab-for-brain-and-cognitive-scientists/2E9F1923DE7B2E625A06AE49E2E88F19
 - https://www.mathworks.com/help/images/segmentation-using-image-segmenter-app.html
