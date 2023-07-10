# Streamlit dashboard
official website : https://streamlit.io/

# what is streamlit
Streamlit is an open-source app framework in python language. It helps us create beautiful web apps for data science and machine learning in a little time. 
It is compatible with major python libraries such as scikit-learn, keras, PyTorch, latex, numpy, pandas, matplotlib, etc.

# SuperStore Data
 This is a sample superstore dataset, a kind of a simulation where you perform extensive data analysis to deliver insights on how the company can increase 
 its profits while minimizing the losses.
 
# virtual environment steps :
 python -m venv venv

 venv\Scripts\activate

 venv\Scripts\deactivate

 pip install -r requirements.txt

 streamlit run app.py

# sample code :
import streamlit as st

import seaborn as sns

st.header("This is simple streamlit application")

st.text("step by step web app learning from creative soft")

df=sns.load_dataset('iris')

st.write(df.head(10))

# Streamlit URL :  [![Python application](https://github.com/kaushik-prasad-dey/Python-Streamlit-dashboard/actions/workflows/python-app.yml/badge.svg)](https://github.com/kaushik-prasad-dey/Python-Streamlit-dashboard/actions/workflows/python-app.yml)

https://interactiveapp.streamlit.app/

# Dashboard Screenshots with Light Mode :
![image](https://github.com/kaushik-prasad-dey/Python-Streamlit-dashboard/assets/109330283/dca6bf8d-49dd-4489-964a-06ec00518aa6)

# Dashboard Screenshots with Dark Mode :
![image](https://github.com/kaushik-prasad-dey/Python-Streamlit-dashboard/assets/109330283/b1aa18ec-2b63-42fd-a737-16a805384e4d)



