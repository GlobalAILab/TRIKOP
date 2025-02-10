# TRIKOP: Exploring Visual Prompting Paradigms for Multi-Grade Knee Osteoarthritis Classification on MRI Images

Welcome to the GitHub repository for our web demo showcasing a diagnostic tool for knee osteoarthritis using MRI images with visual prompting.

## About
This web application is designed to assist in diagnosing knee osteoarthritis by analyzing MRI images with the help of visual prompting techniques. Our tool aims to provide accurate and efficient diagnosis for healthcare professionals and patients.

<img src="https://github.com/GlobalAILab/TRIKOP/blob/main/images/login_page.png" alt="Login page" width="800">

## Getting Started
To commence using the diagnostic tool, follow these steps:
1. Access the [TRIKOP web application](https://trikop.gmedai.com/account/login).
2. Log in with the following credentials:
   - **Username:** userdemo
   - **Password:** demoTRIKOP
4. Choose from one of the preloaded images or upload a new image using the image upload feature. Additional images can be accessed through this [Image demo](https://drive.google.com/drive/folders/1D4e7I7IyGfB4q5mg-vrc0lrMWac6UH8H?usp=drive_link). A slider has been provided for viewing different MRI image slices.
<img src="https://github.com/GlobalAILab/TRIKOP/blob/main/images/upload_image.png" alt="Upload image function" width="400">

5. Once an image is selected, the system will generate various prompting methods along with illustrative images for each method.
   
6. Press the "Diagnose" button with the selected prompting method, allowing the model to conduct a diagnosis and return results, including:
   - Diagnostic probabilities corresponding to each KL disease severity level.
   - An attention map displaying the baseline and visual prompting methods, enabling observation of image regions the model focuses on for decision-making (increasing redness indicates greater model attention in that region).

<img src="https://github.com/GlobalAILab/TRIKOP/blob/main/images/result.png" alt="Diagnostic results" width="800">

## Support
If you have any questions, feedback, or issues related to the web demo, please feel free to contact us at [gmedaiteam@gmail.com]
Thank you for visiting our GitHub repository and exploring our diagnostic tool for knee osteoarthritis using MRI images with visual prompting.
