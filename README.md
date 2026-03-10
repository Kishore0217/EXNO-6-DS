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
Import required Libraries:

```python
import seaborn as sns
import pandas as pd
```
Read the CSV File

```python
df=pd.read_csv("iris.csv")
df.head()
```
Join pLot:

```python
sns.jointplot(x="petal_length", y="petal_width", data=iris, kind="hex")
```
Pairplot:

```python
sns.pairplot(data=iris, vars=["sepal_length","sepal_width"], hue="species")
plt.show()
```
DistPlot:

```python
sns.distplot(iris["petal_length"], kde=True)
plt.show()
```
CountPlot:

```python
sns.countplot(y="species", data=iris)
plt.show()
```
BoxPlot:

```python
sns.boxplot(x="species", y="petal_length", data=iris)
plt.show()
```
BarPlot:

```python
sns.barplot(x="species", y="petal_length", data=iris)
plt.show()
```
ViolinPlot:

```python
sns.violinplot(x="species", y="petal_length", data=iris)
plt.show()
```

# Output:

<img width="733" height="540" alt="Screenshot 2026-03-10 164321" src="https://github.com/user-attachments/assets/ff599ba9-1330-42b9-988e-685e1b2d6f4b" />

<img width="762" height="731" alt="Screenshot 2026-03-10 164438" src="https://github.com/user-attachments/assets/81a8a20d-32ce-49e1-91cb-62ec9b0a5edb" />

<img width="775" height="757" alt="Screenshot 2026-03-10 164404" src="https://github.com/user-attachments/assets/5412b617-2c14-4ebf-bc01-80d02b291c50" />

<img width="753" height="752" alt="Screenshot 2026-03-10 164516" src="https://github.com/user-attachments/assets/d3322cdc-d8ea-4ebb-80cb-5f4429ecaab6" />

<img width="715" height="647" alt="Screenshot 2026-03-10 164550" src="https://github.com/user-attachments/assets/d2c41288-12bc-4e39-8c3e-731220eeb7e4" />

<img width="710" height="473" alt="Screenshot 2026-03-10 164635" src="https://github.com/user-attachments/assets/13a56c9e-2dd7-4285-bebd-b077f4419daa" />

<img width="732" height="519" alt="Screenshot 2026-03-10 164719" src="https://github.com/user-attachments/assets/8b0f928a-8d58-4307-927e-78ff0899c3a6" />

<img width="701" height="502" alt="Screenshot 2026-03-10 164753" src="https://github.com/user-attachments/assets/e1b0ade0-29a5-4212-aded-dfbaad6f1a01" />

<img width="698" height="524" alt="Screenshot 2026-03-10 164853" src="https://github.com/user-attachments/assets/1cedb0f5-f938-41dd-915e-85cad83e1ceb" />

<img width="708" height="527" alt="Screenshot 2026-03-10 164822" src="https://github.com/user-attachments/assets/8944f75e-2eda-4966-99e9-7b87c4c6ec37" />

<img width="780" height="515" alt="Screenshot 2026-03-10 164952" src="https://github.com/user-attachments/assets/f812fb24-86a6-4033-8614-0d9f2d8bc8fe" />

<img width="689" height="512" alt="Screenshot 2026-03-10 165012" src="https://github.com/user-attachments/assets/83289d86-b420-418b-8ee1-e49c6353af27" />

<img width="702" height="499" alt="Screenshot 2026-03-10 165044" src="https://github.com/user-attachments/assets/8cfd5607-dc6c-47fb-a16b-7169214f815e" />

<img width="727" height="560" alt="Screenshot 2026-03-10 165131" src="https://github.com/user-attachments/assets/4a89764e-c5ad-4030-8ddd-19e711e39b57" />

















# Result:
  Thus the Data Visualization was executed Successfully Using the Seaborn.
