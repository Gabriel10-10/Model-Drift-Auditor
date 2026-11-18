
# Model-Drift-Auditor

2023 cochort data

- the class in inbalanced: 0: 3189, 1: 1011
![alt text](image.png)
#### Dropout Rate: 24.07%
- there is no missing value across features
- there are no duplicated student id
- there are duplicated rows
- Correlation between numerical features: there is no strong correlation between features, the only high correlation is between
  **assignments_submitted_pct** and **lms_logins_first4wks**
  ![alt text](image-1.png)

- outlier analysis
![alt text](image-2.png)

- metrics
![alt text](image-3.png)
![alt text](image-4.png)

- 

- grouped metrics
![alt text](image-5.png)

-psi 
![alt text](image-6.png)

- disagreements
![alt text](image-7.png)