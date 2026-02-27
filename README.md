# aws-high-availability-project
Implemented a Fault-Tolerant &amp; Scalable Web Architecture of AWS.

# 🚀 AWS High Availability Architecture Project

## 📖 Project Overview
This project demonstrates how to deploy a highly available and scalable web application using AWS services like EC2, Application Load Balancer, and Auto Scaling Group.

The architecture ensures:
- High Availability
- Fault Tolerance
- Automatic Scaling
- Load Distribution Across Multiple Servers

---

## 🏗️ Architecture Diagram

![Architecture Diagram]

---

## ⚙️ AWS Services Used

- Amazon EC2
- Application Load Balancer (ALB)
- Target Group
- Auto Scaling Group
- Security Groups

---

## 🔄 How It Works

1. Users access the application via Load Balancer DNS.
2. The Application Load Balancer distributes traffic across multiple EC2 instances.
3. Target Group continuously monitors instance health.
4. Auto Scaling Group automatically:
   - Launches new instances when traffic increases
   - Terminates instances when traffic decreases
5. If one EC2 instance fails, traffic is redirected to healthy instances automatically.

---

## 📈 Key Features

✅ High Availability across multiple instances  
✅ Automatic Scaling based on demand  
✅ Health Checks for fault tolerance  
✅ Zero Downtime Architecture  

---

## 🛠️ Deployment Steps

1. Launch EC2 Instance
2. Install Web Server (Apache/Nginx)
3. Deploy Website Code
4. Create Target Group
5. Create Application Load Balancer
6. Attach Target Group to ALB
7. Create Auto Scaling Group
8. Test Scaling & Health Checks

---

## 🧪 Testing Performed

- Verified Load Balancer DNS access
- Checked Target Group health status
- Simulated instance failure
- Verified automatic traffic redirection
- Tested scaling behavior

---

## 🎯 Learning Outcomes

- Practical understanding of AWS networking
- Real-world implementation of High Availability
- Understanding of Load Balancing concepts
- Hands-on experience with Auto Scaling


---

## 👩‍💻 Author

Durva Patil  
Aspiring Cloud Engineer | AWS Enthusiast
