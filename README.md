![workflow](https://github.com/mertmetin1/Performance-Data-Analysis-Based-on-Work-Volume-and-Salary-Metrics/assets/98667673/dfdcfa00-e954-489f-937e-b038a423a5f8)## Performance Data Analysis Based on Work Volume and Salary Metrics With Knime
[TR](https://github.com/mertmetin1/Performance-Data-Analysis-Based-on-Work-Volume-and-Salary-Metrics/files/15411413/Is.Hacmi.ve.Maas.Metriklerine.Calisan.Gore.Performansi.Veri.Analizi.docx)


![Uplo<?xml version="1.0" standalone="no"?>

### Objective
This analysis aims to examine the relationship between employees' demographic information and their job performance within a company. The dataset includes variables such as gender, age, work volume, and salary of employees. The objective is to identify factors affecting job performance and provide recommendations based on the analysis.

### Data Structure
The dataset consists of 200 observations and 5 variables, including 4 numerical and 1 categorical variable. These variables are as follows:
1. No: Observation number
2. Gender: Employee's gender (F: Female, M: Male)
3. Age: Employee's age
4. Volume: Employee's work volume
5. Salary: Employee's salary

### Clustering
In this analysis, K-Means and Hierarchical Clustering models were used. During the clustering process, the salary and volume variables were utilized. Hierarchical Clustering with Euclidean distance was applied to create a clustering dendrogram, and the ideal number of clusters was determined to be 3.
![image](https://github.com/mertmetin1/Performance-Data-Analysis-Based-on-Work-Volume-and-Salary-Metrics/assets/98667673/2c88d7ce-b10b-4be7-a23d-a253bb6de93a)

For K-Means, the centroid distribution static value was set to 123. As a result, the K-Means model was trained for 3 clusters, and the cluster distributions were calculated as follows:
1. Cluster_2 (Low Salary - Low Volume): Male: 55, Female: 39; Total: 94; Percentage: 47.0%
2. Cluster_0 (High Salary - High Volume): Male: 36, Female: 30; Total: 66; Percentage: 33.0%
3. Cluster_1 (High Salary - Low Volume): Male: 21, Female: 19; Total: 40; Percentage: 20.0%

### Evaluation
Basic statistics reveal a positive correlation between salary and volume variables. It was observed that the number of male employees in the low salary and low volume cluster was higher than the number of female employees, while in the high salary and high volume cluster, the number of female employees was higher than the number of male employees. The distribution of salary and volume by age was found to be homogeneous.
![image](https://github.com/mertmetin1/Performance-Data-Analysis-Based-on-Work-Volume-and-Salary-Metrics/assets/98667673/01f2640e-fd32-4b79-8d9e-b7655caada0a)

### Clustering Based on Salary and Volume Variables:
1. High Salary - High Volume Cluster (Cluster 0):
    - Male Ratio: 36 / 112 = 0.3214
    - Female Ratio: 30 / 88 = 0.3409
2. High Salary - Low Volume Cluster (Cluster 1):
    - Male Ratio: 21 / 112 = 0.1875
    - Female Ratio: 19 / 88 = 0.2159
3. Low Salary - Low Volume Cluster (Cluster 2):
    - Male Ratio: 55 / 112 = 0.4911
    - Female Ratio: 39 / 88 = 0.4432
![image](https://github.com/mertmetin1/Performance-Data-Analysis-Based-on-Work-Volume-and-Salary-Metrics/assets/98667673/fe216617-f7ba-4bac-a11b-dadaa30305f1)

In the overall dataset, the proportion of females is 88 / 200 = 0.44, and the proportion of males is 112 / 200 = 0.56.
