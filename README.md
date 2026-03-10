# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding:
Import Required Libraries

```Python
import seaborn as sns
import pandas as pd
```
Read the CSV File

```python
df=pd.read_csv("iris.csv")
df.head()
```
Corelation:

```python
cor=df.corr(numeric_only=True)
cor
```
JointPlot:

```python
sns.jointplot(x='sepal_length', y='sepal_width', data=df, kind='hex', cmap='Blues')
sns.jointplot(x='sepal_length', y='sepal_width', data=df, kind='reg')
```
PairPlot:

```python
sns.pairplot(df)
sns.pairplot(df,hue='sepal_width')
```
DistPlot:

```python
sns.distplot(df['sepal_length'])
sns.distplot(df['sepal_length'])
```
CountPlot:

```python
sns.countplot(x='species',data=df)
sns.countplot(y='species',data=df)
```
BarPlot:

```python
sns.barplot(x='petal_length',y='petal_width',data=df)
sns.barplot(x='petal_width',y='petal_length',data=df)
```
BoxPlot:

```python
sns.boxplot(x='species',y='sepal_width',data=df)
sns.boxplot(x='species',y='sepal_length',data=df,palette='rainbow')
```

```python
sns.boxplot(data=df,orient='v',palette='rainbow')
sns.boxplot(x='sepal_length',y='sepal_width',hue='species',data=df)
```
ViolinPlot:

```python
sns.violinplot(x='sepal_length',y='species',palette='rainbow',data=df)
sns.violinplot(x='sepal_length',y='species',palette='rainbow',data=df)
```

# Output:

<img width="733" height="540" alt="Screenshot 2026-03-10 164321" src="https://github.com/user-attachments/assets/15341f48-6ddd-4e8e-96b2-b8f4230bc5be" />

<img width="775" height="757" alt="Screenshot 2026-03-10 164404" src="https://github.com/user-attachments/assets/b0a204a6-aa9c-4dcc-9d32-07f8e1d21f64" />

<img width="762" height="731" alt="Screenshot 2026-03-10 164438" src="https://github.com/user-attachments/assets/c90c2046-3319-4b49-9e40-7b536b403607" />

<img width="753" height="752" alt="Screenshot 2026-03-10 164516" src="https://github.com/user-attachments/assets/e9cbd06c-c304-43f7-a0b9-cdc3432f1c4f" />

<img width="715" height="647" alt="Screenshot 2026-03-10 164550" src="https://github.com/user-attachments/assets/c9eb1300-b6d9-40d4-a911-16b06e12f6da" />

<img width="710" height="473" alt="Screenshot 2026-03-10 164635" src="https://github.com/user-attachments/assets/e91a6893-2610-4b88-a18f-708083167265" />

<img width="732" height="519" alt="Screenshot 2026-03-10 164719" src="https://github.com/user-attachments/assets/2224cee4-ffc0-4faf-8ae7-b08a7ffcd810" />

<img width="701" height="502" alt="Screenshot 2026-03-10 164753" src="https://github.com/user-attachments/assets/1fc7ff40-1938-4ca6-aa42-52e3e14a3c10" />

<img width="708" height="527" alt="Screenshot 2026-03-10 164822" src="https://github.com/user-attachments/assets/c49e92c2-f7f5-4d0a-b313-c301f45cd581" />

<img width="698" height="524" alt="Screenshot 2026-03-10 164853" src="https://github.com/user-attachments/assets/76eecd7c-b4f5-46b1-8df7-945cb0fa4a27" />

<img width="736" height="507" alt="Screenshot 2026-03-10 164925" src="https://github.com/user-attachments/assets/b1aa9446-33e6-4104-b9cc-df9347bfecd7" />

<img width="780" height="515" alt="Screenshot 2026-03-10 164952" src="https://github.com/user-attachments/assets/d6505d43-3e85-4cdd-be08-6ebdc66d0a23" />

<img width="702" height="499" alt="Screenshot 2026-03-10 165044" src="https://github.com/user-attachments/assets/37c89800-5948-4e22-b40b-8c3983051794" />

<img width="727" height="560" alt="Screenshot 2026-03-10 165131" src="https://github.com/user-attachments/assets/728868d2-c1e3-4a0e-8447-be4b6ec59106" />















# Result:
Thus the Data Visualisation was successfully done Using seaborn.
