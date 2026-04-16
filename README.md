# Hi there, I'm ABDULGANIY BASIRAH OLANIKE! 👋
### 🚀 Aspiring DevOps Engineer | Cloud Enthusiast | Infrastructure as Code Advocate

I am a tech student based in **Nigeria 🇳🇬**, currently executing a dedicated **6-month roadmap** to transition into Cloud Engineering and DevOps. I am passionate about automating infrastructure and building scalable systems on AWS.

---

## 👨‍💻 About Me

I'm a passionate tech enthusiast transitioning into DevOps and Cloud Engineering. I believe in **"Infrastructure as Code"** not just as a tool, but as a philosophy for building reliable, scalable, and reproducible systems. When I'm not automating AWS infrastructure, I enjoy documenting my learning journey to help others in the DevOps community.

**My approach:** Learn → Build → Document → Repeat.

---

## 🔧 Skills & Technologies
- **Cloud:** AWS (EC2, S3, IAM, VPC, Auto Scaling, ALB, CloudWatch, SNS) - *Advanced*
- **DevOps & IaC:** Terraform, Packer, Ansible, Linux, Networking, Docker Swarm - *Intermediate to Advanced*
- **CI/CD:** GitHub Actions (Self-cleaning pipelines, Matrix builds, Trivy security scans) - *Intermediate*
- ** Middleware: Nginx (Reverse Proxy/WebSockets), Redis - Intermediate
- **Programming:** JavaScript, TypeScript, PHP, SQL, Node.js
- **Frameworks:** React, Next.js, Angular, Vue, Laravel
- **Tools:** Git, GitHub, VS Code
  
---

## 🏅 Certifications

- **AWS Certified Cloud Practitioner** *(In Progress)*
- **Terraform Associate** *(Planned for Q2 2026)*

---

## 🚀 Now
- 📚 Studying for AWS Cloud Practitioner
- 🔧 Building a Kubernetes cluster on AWS
- 📝 Writing about Terraform best practices

---

## 🏆 Featured Projects (The Portfolio)
*Evidence of my hands-on experience with AWS and Infrastructure.*


### 🚀 [Real-Time Microservices Voting Infrastructure](https://github.com/Nikkypwetti/devops-learning-journey/tree/main/04-containerization/projects/microservices/voting-app-project)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**The Challenge:** Orchestrate a complex, multi-language microservices stack while maintaining data consistency across asynchronous services and enabling real-time UI updates behind a secure gateway.

**Solution Highlights:**
- **Orchestration:** Deployed a 5-tier stack (Python, .NET, Node.js, Redis, Postgres) using Docker Swarm for high availability
- **Real-Time Data Flow:** Reconfigured Nginx as a Reverse Proxy to support WebSocket (Socket.io) "Upgrade" handshakes for live dashboard updates
- **Security-First Config:** Implemented Docker Secrets for zero-trust database authentication, eliminating insecure environment variables
- **Event-Driven Architecture:** Leveraged Redis as a message broker to decouple high-frequency voting from database write persistence
- **Hardened CI/CD:** Built a multi-service GitHub Actions pipeline featuring Trivy vulnerability scanning for all container images
- **Outcome:** Achieved sub-second result propagation and established a secure, reproducible infrastructure-as-code deployment

**Tech Stack:** Docker Swarm, Nginx, Redis, PostgreSQL, Node.js, .NET Core, Python, GitHub Actions, Trivy

[➡️ View the Microservices Code & Documentation](https://github.com/Nikkypwetti/devops-learning-journey/tree/main/04-containerization/projects/microservices/voting-app-project)

---

### 🚀 [Automated Golden AMI Pipeline (CI/CD)](https://github.com/Nikkypwetti/devops-learning-journey/tree/main/03-infrastructure-as-code/projects/golden-ami-pipeline)

![Packer](https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-000000?style=for-the-badge&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS Builder](https://img.shields.io/badge/AWS-Builder-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

**The Challenge:** Eliminate manual configuration drift and ensure "Immutable Infrastructure" by automating the creation of hardened, versioned Amazon Machine Images.

**Solution Highlights:**
- **Image Baking:** Used Packer with Ansible provisioner to create secure, pre-configured AMIs
- **Secret Management:** Integrated Ansible Vault for encrypted credentials and configurations
- **Cost Optimization:** Automated cleanup of old AMIs and EBS snapshots
- **Monitoring:** Terraform-provisioned CloudWatch dashboard for real-time resource monitoring
- **CI/CD Ready:** Pipeline triggers on code commit → build → test → deploy
- **Outcome:** Reduced AMI creation time by 85% and eliminated configuration drift

**Tech Stack:** Packer, Ansible, Terraform, AWS (EC2, CloudWatch, S3), Bash

[➡️ View the Pipeline Code & Documentation](https://github.com/Nikkypwetti/devops-learning-journey/tree/main/03-infrastructure-as-code/projects/golden-ami-pipeline)

---

### [AWS Infrastructure Automation (Terraform)](https://github.com/Nikkypwetti/practice)
*I practice EC2 Instance with Terraform provisioner and Data sources.*

![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**The Challenge:** Automate a full VPC network and web server deployment to reduce manual configuration errors.
- **Tech Stack:** Terraform, AWS (EC2, VPC, S3), Nginx.
- **Key Highlight:** Implemented `remote-exec` provisioners to achieve a "Zero-Touch" deployment where the server is fully configured upon creation.
- **Outcome:** Reduced environment setup time from 20 minutes to 2 minutes.

[➡️ View the Code & Architecture graph](https://github.com/nikkypwetti/practice)

---

### [AWS Multi-Tier Architecture with Terraform](https://github.com/Nikkypwetti/aws-terraform-multi-tier-app)
*I built a production-ready, 2-tier web architecture completely defined as code.*

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

**What I built:**
* **Infrastructure as Code:** Replaced manual console clicking with reusable Terraform modules.
* **Networking:** Custom VPC with Public/Private subnet isolation across 2 Availability Zones.
* **Security:** Implemented least-privilege Security Groups for EC2 and RDS.
* **Compute:** Auto-provisioned Amazon Linux 2023 web servers with Bash user-data scripts.

[➡️ View the Code & Architecture Diagram](https://github.com/Nikkypwetti/aws-terraform-multi-tier-app)

---


### ☁️ [High-Availability Web Application](https://github.com/Nikkypwetti/aws-ha-webapp)
**Tech:** *AWS EC2, Auto Scaling Groups, Application Load Balancer, VPC, Linux*
> Designed and deployed a fault-tolerant, multi-AZ web architecture. Implemented chaos engineering to test resilience against Availability Zone failures.

[➡️ **View Architecture & Code »**](https://github.com/nikkypwetti/aws-ha-webapp)

---


## 📚 My Learning Journey (The Process)
I document everything I learn daily—mistakes, fixes, and labs—in my open-source notebook. This demonstrates my consistency and ability to document technical concepts.

* 📖 **[Read my Daily DevOps Notes & Labs](https://github.com/Nikkypwetti/devops-learning-journey)**

---

## 🌱 Currently Learning
- CI/CD pipelines
- Advanced Terraform modules
- Cloud security & monitoring

---

## 🛠️ Tools & Technologies
**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Scripting & Version Control**
![Bash Scripting](https://img.shields.io/badge/Bash_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

**Currently Learning**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)

---

## 📈 Activity Overview
- 🔭 **Currently Working On:** DevOps & Cloud projects
- 🌱 **Learning:** CI/CD, Terraform, Cloud Security
- 📊 **Recent Activity:** Building automated AWS infrastructure
- 📝 **Documenting:** [DevOps Learning Journey](https://github.com/Nikkypwetti/devops-learning-journey)

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Nikkypwetti&show_icons=true&theme=radical&hide_border=true&cache_seconds=86400" alt="Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nikkypwetti&layout=compact&theme=radical&hide_border=true&cache_seconds=86400" alt="Languages" width="45%" />
</p>

---

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=Nikkypwetti&theme=radical&column=7)](https://github.com/ryo-ma/github-profile-trophy)

---

## 📫 Connect with Me
* **LinkedIn:** [linkedin.com/in/ganiyu-basirat](https://linkedin.com/in/ganiyu-basirat)
* **Email:** [olanike.basirat620@gmail.com](mailto:olanike.basirat620@gmail.com)
