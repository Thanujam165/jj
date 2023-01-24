import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
df=pd.read_csv("C:/Users/Mahesh Thhadur/Downloads/archive/Iris.csv")
df

df.describe()

df.isnull().sum()

del df['Id']

df

df.shape

df_setosa=df.loc[df['Species']=='Iris-setosa']

df_setosa=df.loc[df['Species']=='Iris-setosa']

df_setosa=df.loc[df['Species']=='Iris-setosa']
