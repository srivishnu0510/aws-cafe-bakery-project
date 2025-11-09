# ☁️ AWS Café & Bakery Project

A cloud-based three-tier web application deployed on **Amazon Web Services (AWS)**, following the **AWS Well-Architected Framework**.  
This project demonstrates infrastructure automation, scalability, and secure deployment of a simple café and bakery management web application.

---

## 🧩 Project Overview

The **AWS Café & Bakery Project** showcases how to design, build, and deploy a secure and scalable web application using AWS core services.  
The infrastructure is provisioned using **AWS CloudFormation**, ensuring repeatability and compliance with best practices.

---

## 🏗️ Architecture

The architecture is based on a **3-tier design**:

1. **Presentation Layer:** Flask web application hosted on an **EC2 instance**.  
2. **Application Layer:** Managed through an **Application Load Balancer (ALB)** for high availability and fault tolerance.  
3. **Data Layer:** **Amazon RDS (MySQL)** database hosted in a private subnet for secure data storage.

### 🧱 Components Used
| AWS Service | Purpose |
|--------------|----------|
| **Amazon VPC** | Provides network isolation and segmentation into public/private subnets. |
| **Amazon EC2** | Hosts the Flask-based application in the public subnet. |
| **Application Load Balancer (ALB)** | Distributes traffic evenly across EC2 instances. |
| **Amazon RDS (MySQL)** | Provides a secure, managed database service in the private subnet. |
| **Amazon S3** | Stores application code and static assets. |
| **AWS CloudFormation** | Automates infrastructure provisioning using Infrastructure as Code (IaC). |
| **Amazon CloudWatch** | Monitors system performance and logs application metrics. |

---

## 🖼️ Architecture Diagram

<img width="1536" height="1024" alt="architecture" src="https://github.com/user-attachments/assets/3d47754a-db61-4a79-a6a1-fa1a1cf09bce" />

---

## 🚀 Deployment Steps

1. **Upload Application Files:**  
   Upload `app.zip` containing the Flask application to **Amazon S3**.

2. **Deploy Infrastructure:**  
   Launch the stack using the provided **CloudFormation template** (`vpc-cafe-bakery.yaml`).

3. **Database Configuration:**  
   Configure **RDS MySQL** connection credentials and link the EC2 instance to the database.

4. **Application Deployment:**  
   Connect to the EC2 instance, download the app code from S3, and run the Flask application.

5. **Access the Application:**  
   Retrieve the **ALB DNS name** from the AWS Management Console and access the running web app.

---

## 📸 Screenshots


**Web Application Output**  
<img width="1366" height="768" alt="stack visual services" src="https://github.com/user-attachments/assets/239809de-b585-46e7-8f5d-1d4156557a07" />
<img width="1366" height="768" alt="stack creation" src="https://github.com/user-attachments/assets/fac26a3b-b903-4a20-bb52-164763b70e5a" />
<img width="1366" height="768" alt="output" src="https://github.com/user-attachments/assets/0481972e-8c10-42d0-a331-978bc3d5a087" />


---

## 🎯 Outcome

- ✅ Successfully deployed a **3-tier web application** on AWS.  
- ✅ Demonstrated **Infrastructure as Code (IaC)** using AWS CloudFormation.  
- ✅ Implemented **secure networking** using VPC, subnets, and IAM roles.  
- ✅ Configured **monitoring and logging** via AWS CloudWatch.  
- ✅ Delivered a **scalable and cost-efficient** architecture following AWS best practices.

---

## 📦 Repository Structure
aws-cafe-bakery-project/
│
├── app/
├── templates/
├── screenshots/
│ ├── architecture.png
│ └── output.png
├── vpc-cafe-bakery.yaml
├── requirements.txt
└── README.md


---

## 🧠 Key Learning Outcomes

- Understanding of **AWS networking and subnet design**.  
- Hands-on experience with **Infrastructure as Code (IaC)**.  
- Implementation of **monitoring and automation** for production-grade systems.  
- Improved knowledge of **Flask application deployment** on cloud infrastructure.

---

## 🔗 Project Link

**GitHub Repository:**  
👉 [https://github.com/srivishnu0510/aws-cafe-bakery-project](https://github.com/srivishnu0510/aws-cafe-bakery-project.git)

---

## 👨‍💻 Author

**Sri Vishnu**  
Cloud & DevOps Enthusiast ☁️ | Passionate about Automation, Security, and Scalable Architecture  
📫 Connect on [LinkedIn](https://www.linkedin.com/in/sri-vishnu-64601816b/) | 🖥️ [GitHub](https://github.com/srivishnu0510)

---

## 🏷️ Tags
`AWS` `CloudFormation` `DevOps` `Flask` `EC2` `RDS` `S3` `VPC` `CloudWatch` `Automation` `Infrastructure-as-Code`

---
