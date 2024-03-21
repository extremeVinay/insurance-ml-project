# End to end Insurance-ml-project" 

 ## Introduction About the Data :
  The goal of this project is to give people an estimate of how much they need based on
  their individual health situation. After that, customers can work with any health 
  insurance carrier and its plans and perks while keeping the projected cost from our 
  study in mind. This can assist a person in concentrating on the health side of an   
  insurance policy rather than the ineffective part.

## Context
The insurance.csv dataset contains 1338 observations (rows) and 7 features (columns). The dataset contains 4 numerical features (age, bmi, children and expenses) and 3 nominal features (sex, smoker and region) that were converted into factors with numerical value designated for each level.

## Acknowledgements
Insurance.csv file is obtained from the Machine Learning course website (Spring 2017) from Professor Eric Suess at http://www.sci.csueastbay.edu/~esuess/stat6620/#week-6.

## Inspiration
The purposes of this exercise to look into different features to observe their relationship, and plot a multiple linear regression based on several features of individual such as age, physical/family condition and location against their existing medical expense to be used for predicting future medical expenses of individuals that help medical insurance to make decision on charging the premium.

## Demo Video link
https://youtu.be/cPIuMTkU_u0

# AWS Deployment(using CI-CD piplines) Link :
1. http://44.202.83.52:8080/
2. http://44.202.83.52:8080/predictdata

## Screenshots


![Firefox_Screenshot_2023-07-30T06-18-40 165Z](https://github.com/extremeVinay/insurance-ml-project/assets/105208245/72ea0ad3-f6b4-402c-9b12-6671f90561b0)


![30 07 2023_13 ![Uploading Firefox_Screenshot_2023-07-30T06-18-40.165Z.png…]()
04 41_REC](https://github.com/extremeVinay/insurance-ml-project/assets/105208245/0b305da0-37ce-421c-a8d9-7b73416347bf)

![30 07 2023_13 05 12_REC](https://github.com/extremeVinay/insurance-ml-project/assets/105208245/5f601ccc-9412-4680-840c-dc3d6277d5df)

![30 07 2023_13 06 16_REC](https://github.com/extremeVinay/insurance-ml-project/assets/105208245/b2efb238-dad5-4f83-8271-3aa865aa86d9)


Power bi report link: https://app.powerbi.com/groups/me/reports/5dc00ee8-f951-4fbf-a71d-94356a3f7939/ReportSection64fdae91b940670841cb?experience=power-bi
![Screenshot_2023-09-26_13-03-37](https://github.com/extremeVinay/insurance-ml-project/assets/105208245/304a8d80-de21-4977-b94d-19d41e1b0352)



## PROJECT: Medical Cost Prediction with Docker, AWS, and CI/CD Pipelines

## Situation:
In the healthcare industry, accurately predicting medical costs is crucial for insurance companies, healthcare providers, and policymakers to manage resources effectively and plan budgets.

## Task:
The project aimed to develop a machine learning model for predicting medical costs based on individual patient characteristics, leveraging Docker for containerization, AWS for cloud deployment, and implementing CI/CD pipelines for automated testing and deployment.

## Action:

### Data Collection and Preprocessing:

1) Gathered a comprehensive dataset of medical records, including patient demographics, medical history, and healthcare costs.
Preprocessed the data to handle missing values, encode categorical variables, and normalize numerical features.
Model Development:

2) Developed a machine learning model using regression techniques to predict medical costs based on patient attributes.
Experimented with various algorithms such as linear regression, decision trees, and ensemble methods to identify the best-performing model.
Docker Integration:

3) Containerized the machine learning model using Docker, ensuring consistent performance across different environments and simplifying deployment.
AWS Deployment:

4) Deployed the Dockerized model to AWS cloud infrastructure, leveraging services such as Amazon EC2 for hosting and Amazon S3 for data storage.
Configured auto-scaling and load balancing to handle varying levels of demand and ensure high availability of the prediction service.
CI/CD Pipelines:

5) Implemented CI/CD pipelines using tools like Jenkins or GitLab CI to automate the testing and deployment process.
Set up automated tests to validate model performance and integration tests to ensure compatibility with other components.

## Result:
The Medical Cost Prediction project delivered a scalable and reliable machine learning solution for estimating medical expenses:

The Dockerized model ensures portability and consistency, allowing seamless deployment across different environments.
AWS deployment enables scalable and cost-effective hosting, ensuring reliable access to the prediction service.
CI/CD pipelines automate testing and deployment, reducing manual errors and accelerating the delivery of updates and improvements to the prediction model.
By leveraging Docker, AWS, and CI/CD pipelines in the medical cost prediction project, healthcare organizations can streamline their cost estimation processes, improve resource allocation, and ultimately enhance the quality of patient care.












