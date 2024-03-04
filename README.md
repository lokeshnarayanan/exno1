# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
```
Developed by: Lokesh N

Register no: 212222100023
```

### 1) Read and display DataFrame
```python
import pandas as pd
df=pd.read_csv('/content/SAMPLEIDS.csv')
df
```
## OUTPUT:

![Screenshot 2024-03-01 154736](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/4e49fcac-4e45-4609-9919-6efd2045f70d)
### 2) Display head
```python
df.head()
```
## OUTPUT:

![Screenshot 2024-03-01 154809](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/756af652-2e9c-4f75-8f04-7087b30789b4)
### 3) Display tail
```python
df.tail()
```
## OUTPUT:

![Screenshot 2024-03-01 154831](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/9b2316aa-b545-4a89-9731-3fe81b08f273)
### 4) Info of datafram
```python
df.info()
```
## OUTPUT:

![Screenshot 2024-03-01 154858](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/4b6c1206-0fb6-4ab6-8b0d-b71d9301d31e)
### 5) Describe about the dataframe
```python
df.describe()
```
## OUTPUT:

![Screenshot 2024-03-01 154925](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/8c9def69-0199-4ebf-9365-ffc999b7f340)
### 6) Shape of the datafram
```python
df.shape
```
## OUTPUT:

![Screenshot 2024-03-01 154945](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/b138cb78-9d96-43a0-939f-fddfb85f83d0)
### 7) Checking tha NUll values
```python
df.isnull()
```
## OUTPUT:

![Screenshot 2024-03-01 155024](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/0fe6f2f1-4bca-4727-a239-a54eb6b37d07)
### 8) Drop the Null values
```python
df.dropna(axis=0)
```
## OUTPUT:

![Screenshot 2024-03-01 155135](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/bd430e52-ca9c-4d1f-a03b-1a0778e27e6f)
### 9) Fill the Null values
```python
df.fillna(0)
```
## OUTPUT:

![Screenshot 2024-03-01 155150](https://github.com/chandrumathiyazhagan/exno1/assets/119393023/582708d0-abc7-4c18-8c89-5698d2b80ef3)

### Result

The data cleaning has beeen done successfully.
