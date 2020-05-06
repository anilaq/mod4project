# mod4project
This project will be on image classification with deep learning. 


We will be taking the famous chest x-ray dataset off of Kaggle found here https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
Through Convolutional Neural Networks I will conduct an image classification to determine which pediatric patients have 
pneumonia. 

In order to predict whether a pediatric patient has a normal chest x-ray vs an x-ray that shows pneumonia I must be able to build a working model. I will be using the OSEMN process as stated in the project requirements. Note that scrubbing was not necessary. My jupyter notebook will be organized in the following way:
    1. ***O*** btaining the data from kaggle is listed at the top. 
    2. Importing the right tools, libraries and layers
    3. ***E*** xploratory Data Analysis: what does the data tell us?!
    4. ***Model***: Baseline model: this will give us more of an understanding of overfitting
    5. Data Augmentation: through this process we will identify the best predictions that reduce overfitting. 
    6. ***iNterpret*** /Evaluate our best model with: 
        - confusion matrix 
        - predict proba 
        - threshold selection 