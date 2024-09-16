<h1 align="center">City of Vancouver Project Part 3 Assignment</h1>
<p align="center">
Peddaballe Vinodh Kumar Reddy [2212316] <br>
University Canada West<br>
BUSI 653, Section 04<br>
Instructor: Mahmood Mortazavi Dehkordi<br>
Due Date: 15th September 2024<br>
</p>

___

# Project Description: Cost estimation of Lost and Found Animal Records DAP
In this assignment I will be describing the cost details of AWS Services used for the City of Vancouver project mainly about the Data concerns of the Data Analytic Platform (DAP) implemented previously. For this assignment. In this scenario we will be calculating the cost incurred monthly for setting up the network along with all the services using in the process of DAP. We will be explaining the scenario based on the image below which shows our DAP network details. We will also use the same for calculating cost using “AWS Calculator”.
![figure 47](https://github.com/user-attachments/assets/cfc3c7c7-7b62-4c2a-a556-121259b0f44d)
* The above image displays the network used for my DAP model.
## Project Title: Understanding Cost Estimation of DAP
The primary need of this project is to conduct a exploratory analsis of the process of estimating the average monthly costs for the AWs services we will be using.
## Project Objective:
* Cost Estimation of AWS Services Used.
## Methodology
* We will be using the [AWS Pricing Calculator](https://calculator.aws/#/) to estimate the cost that we may incur during the DAP process of Lost and Found Animal Records for City of Vancouver.
### S3 Cost Estimation
* S3 Data Used Information<br>
![figure 48](https://github.com/user-attachments/assets/e4905568-8b09-4f1e-94e4-6e235b24bede)
* The above image displays the date or material used for our DAP model.
* Our team is assuming that we will be using around 4GB of data every month with close to 4500-5000 requests for both the categories of put and get sections. We also assumed we will be using around 2GB of returned data and scanned data respectively. The cost estimation is as shown below.<br>
![figure 49](https://github.com/user-attachments/assets/903ab07a-9c20-4c15-91c0-35fbe159f608)
* The above image displays the cost of S3 per month approximately.
* Similarly for data transfer to and from S3 are also shown below.<br>
![figure 50](https://github.com/user-attachments/assets/ba468c9b-6251-4c8c-9ef1-4d57a9295335)
* Our team assumes we will be using around 12 GB data to send to S3 via internet and nothing our of the S3.
### AWS Glue Cost Estimation<br>
![figure 51](https://github.com/user-attachments/assets/3631de4b-bd95-4033-b6de-b883a3a35ec7)
* The above image displays the cost of AWS Glue per month approximately.
### VPC Cost Estimation<br>
![figure 52](https://github.com/user-attachments/assets/2daa80d0-16f2-475f-9813-9b1740b4c9bb)
* The above image displays the cost of AWS VPC per month approximately.<br>
 ![figure 53](https://github.com/user-attachments/assets/fc4b7be7-4e23-43a7-8503-786e30c1786b)
* The above image displays the cost of AWS VPC per month approximately.
### API Gateway Cost Estimation<br>
![figure 54](https://github.com/user-attachments/assets/a74e4726-2d08-4d6c-a87d-6c0bfe04547e)
* The above image displays the cost of AWS API Gateway per month approximately.
### AWS Athena Cost Estimation<br>
![figure 55](https://github.com/user-attachments/assets/4043be2e-22c7-4fee-851f-6cba5b7b2dac)
* The above image displays the cost of AWS Athena per month approximately.
### AWS EC2 Cost Estimation
![figure 56](https://github.com/user-attachments/assets/c4e3d14a-75da-4fc1-b720-f8a8056d7a02)
* The above image displays the cost of AWS EC2 per month approximately.<br>
![figure 57](https://github.com/user-attachments/assets/546688da-bc0f-4c7b-88e8-50e7b1982b10)
* The above image displays the cost of AWS EC2 per month approximately.<br>
![figure 58](https://github.com/user-attachments/assets/c4ffa339-8e84-4313-8c76-8257dcb3ae67)
* The above image displays the cost of AWS EC2 per month approximately.<br>
![figure 59](https://github.com/user-attachments/assets/5cb14479-b63d-4533-8b62-a01ee66bc54a)
* The above image displays the cost of AWS EC2 per month approximately.
### AWS Final Cost Estimation <br>
![figure 60](https://github.com/user-attachments/assets/01e1c55d-fc45-4ef8-bc86-ffd7b4b95d54)
* The above image displays the final cost of various AWS services per month.
* From above figure we can see the final cost estimation comes around “$847.92” USD.
* This includes all the billable services we are using in our DAP network showcased in the figure.
* We also displayed various intermediate costs involved along with the data selected for the services in detail.
