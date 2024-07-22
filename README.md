**INDUSTRIAL COPPER MODELLING**

**INTRODUCTION**

The objective of the indutrial copper analysis is to predict the selling price of the copper. The application gives the price predicition based on the user requirements.

**Python Libraries**

The following mentioned libraries are used to build the application

**Scikit-learn**: import sklearn

**IMBlearn**: from imblearn.combine import SMOTEENN

**Pandas, Numpy**:	import pandas as pd, import numpy as np

**Dash board libraries**-**Streamlit, Seaborn, Matplotlib**:	import streamlit as st, import seaborn as sns, from matplotlib import pyplot as plt

**GUIDE** 

**1.	Predict Selling Price** – Predict selling price allows you to input the user requirements and then predicts the selling price of the copper.

<img width="418" alt="image" src="https://github.com/user-attachments/assets/8a81c70d-e67e-4b79-b908-b9e34abee668">

**2.	Predict Status** – Predict status allows you to input the user requirements and then predicts the status of the deal whether it is won or lost.

<img width="416" alt="image" src="https://github.com/user-attachments/assets/1ce0629c-fbd6-4e34-bf99-0dfe2313a780">


**Data preprocessing and Data Visualization**

Data preprocessing was performed using pandas, numpy and data visualization was performed using seaborn and matplotlib. After the data preprocessing classification model and regression model
was built using sklearn. Randomforest classifier gave an testing accuracy of 99 % for prediciting the status and Randomforest regressor gave an accuracy of 95.9 % for prediciting the selling
price of the copper. Data imbalance in the classification model was handled by using SMOTEENN and it gave us the best results.






