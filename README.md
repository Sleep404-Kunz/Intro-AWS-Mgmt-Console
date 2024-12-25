# Intro-AWS-Mgmt-Console

## Objectives:
1. Describe purpose of AWS Mgmt Console.
2. Navigate the features and functions of the Mgmt Cocsole.
3. Discuss the structure of the AWS global infrastructure
4. Identify AWS payment models and service cost factors.

## 🗺️Navigating the AWS Mgmt Console 
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/1.png" alt = "Output" width = "700" />

AWS Managment Console is a web application that comprises and refers to a broad collection of service consoles for managing AWS resources. Above you can see the home page which provides access to each serivce console and offers a single place to access the information that you need to perform your AWS related tasks. Widgets can be added, rearranged or removed to meet your needs.

<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/2.png" alt = "Output" width = "700" />
You can add the widgets from the home page with the add widgets option, it has mutliple options as can be seen above. To move the widgets and rearrange them, choose the title bar of the widget to drag and drop the widget. To resize the widget click the widget menu indicated by the three dots on the top corner, and choose change size. To remove the widget click the widget menu and click on remove widget. A reset options is also available. 

Widgets frequently used can be added to your favourites list. This list is stored on your browser cookies so clearing your cookies will also remove the fvourites list. Changes to your console wont affect the view of shared users. Widgets cannot be created or customized. 

Serivces can be accessed in one of 3 ways:
1. Use the search bar in the navigation bar. Choose the desired service. Clicking on the star near the service adds them to the favourite serivce widget.
2. Use the recently visited serivce and click on the view all serivces if required to open a list of all the serivce and select the desired service.
3. Use the services menu on the navigation bar, that has a list of all the serivces, favourites, recently visited and another section with the service category.

  <img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/3.png" alt = "Output" width = "700" /> 

## 🧾Billing Considerations
AWS services are affected by region and the payment models. AWS cost explorer can be used to view and analyze teh costs and usage.
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/4.png" alt = "Output" width = "700" />

A region is an isolated geographic area where AWS data centers house the hardware that is used for building cloud infrastructure. The AWS regions are regularly updated and can be found in the following link (https://aws.amazon.com/about-aws/global-infrastructure/). The region affects the latency of the service, cost and availability. However the access to data, security and capacity are not impacted.

AWS regions consists of one or more isolated locations known as Availbility zones. Availability zones comprises data centers with ultra-low latency and redundancy. They are connected to each other and the Internet so that they won't be simultaneously impacted by a shared fate scenario like earthquake or common points of failure like power generators.
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/5.png" alt = "Output" width = "700" />

### AWS payment models
1. Pay as you go: Pay only for individual that you need as long as you use them. No contracts or licensing. ***Agile, Responsive, Scalable*** 
2. Save when you commit: 1 year or 3 year term contract of consistent usage. Provides savings and advantages like recommendations, performance reporting, and budget alerts. ***Better savings*** 
3. Pay less by using more: Volume based discounts. Option for combination of storage and compute resources depending on need to cut costs. ***Increase cost return on scaled services.***

***Free tier of 1 year for new customers to experiment and find the right fit. 3 types of offers***
1. Free trials: Short term free trial starting with activation of a service.
2. 12 months free: Expires 1 year after sign-up. (Does not cover high performance compute instances)
3. Always free: Avaialbe to all AWS customers based on quotas and configurations.

Using the AWS Cost Management tool provides default reports to visualize cost and usage at a high level for AWS accounts and services or at the resource level.

## 💻 Hands on Practice
The image below shows the different AWS service categories. 
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/6.png" alt = "Output" width = "350" />

In addition to Regional and zonal AWS services, there is a set of AWS services whose control planes and data planes don't exist independently in each region. These are called Global. 
The Global services still have separated control and data planes to achieve static stability. The control plane is hosted in a single AWS region while their data plane is globally distributed. 

### *EC2 service* 
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/7.png" alt = "Output" width = "700" />

EC2 is a regional services, currently in Ohio region. All data are the resources provisioned in the Ohio Region. Different regions would have different resources provisioned according to the requirements. 
EC2 also has a global view that shows the instances running in different regions. 
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/8.png" alt = "Output" width = "700" />

### *RDS service (Relational Database Service)* 
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/9.png" alt = "Output" width = "700" />

RDS is not a global service. It is important to make careful considerations about where to provision the resources according to what regions have the resources. 

### *VPC service (Virtual Private Cloud)*
Be sure to select the correct region so that the cost of the serivces used is accurate and matches the region your services are in. An example is shown with the VPC service below. 
<img src= "https://github.com/Sleep404-Kunz/Intro-AWS-Mgmt-Console/blob/main/10.png" alt = "Output" width = "700" />


