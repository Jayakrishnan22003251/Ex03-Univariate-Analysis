# Ex03-Univariate-Analysis

## AIM:
To read the given data and perform the univariate analysis with different types of plots.

## EXPLANATION:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

## ALGORITHM:

### STEP1:
Read the given data
### STEP2:
Get the information about theb data.
### STEP3:
Remove the null values from the data.
### STEP4:
Mention the datatypes from the data.
### STEP5:
Count the values from the data.
### STEP6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

## PROGRAM:
DEVELOPED BY: JAYAKRISHNAN L B L
REG NO: 212222230052
```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
df
df.head()
df.info()
df.describe()
df.isnull().sum()
df.dtypes
df['Postal Code'].value_counts()
sns.boxplot(x="Postal Code", data=df)
sns.countplot(x="Postal Code", data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x="Postal Code", data=df)
```
## OUTPUT:
### Dataset:
![Screenshot 2023-04-01 082510](https://user-images.githubusercontent.com/120232371/229262491-b1fc5dbf-280b-42d8-a5b3-61c86c7a5f4f.png)
### Head:
![Screenshot 2023-04-01 082636](https://user-images.githubusercontent.com/120232371/229262559-6dfc6af4-94ef-4afa-aad7-0d226405ab52.png)
### Info:
![Screenshot 2023-04-01 082836](https://user-images.githubusercontent.com/120232371/229262596-78c99f86-ee67-4bb3-b301-d7f399429a84.png)
### Describe:
![Screenshot 2023-04-01 083015](https://user-images.githubusercontent.com/120232371/229262678-c1c82255-c25d-477e-a834-e11ff9f851b8.png)
### Isnull:
![Screenshot 2023-04-01 083211](https://user-images.githubusercontent.com/120232371/229262745-6e4a2b8a-496e-4432-9188-9fce18299bbc.png)
### Datatypes:
![Screenshot 2023-04-01 083303](https://user-images.githubusercontent.com/120232371/229262769-b82b7071-3f11-4f1d-a485-56d66660248c.png)
### Value count:
![Screenshot 2023-04-01 083419](https://user-images.githubusercontent.com/120232371/229262805-80b9f131-cbff-4489-982c-8ed967e3074c.png)
### Boxplot:
![Screenshot 2023-04-01 083501](https://user-images.githubusercontent.com/120232371/229262828-c7e1af25-cf8c-4643-8f58-59aba3e4fb52.png)
### Countplot:
![Screenshot 2023-04-01 083625](https://user-images.githubusercontent.com/120232371/229262846-29b9bd36-4986-44e7-b2a8-be2a61a1f6e7.png)
### Distribution plot:
![Screenshot 2023-04-01 083745](https://user-images.githubusercontent.com/120232371/229262890-76363b62-936a-463d-bbc4-fd403ddef603.png)
### Histogram plot:
![Screenshot 2023-04-01 083836](https://user-images.githubusercontent.com/120232371/229262915-f4f6a575-a258-4bfc-88af-6c2388734e0e.png)

## RESULT:
Thus we have read the given data and performed the univariate analysis with different types of plots.








