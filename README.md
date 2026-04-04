<div align="center">

# 👋 Hi, I'm Ashutosh Banswal

### DevOps Engineer | AWS · Kubernetes · Terraform · Jenkins · Docker

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashutosh-banswal-front-end-developer)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashubanswal1998@gmail.com)
[![Location](https://img.shields.io/badge/📍_Pune,_India-Remote_Open-28a745?style=for-the-badge)](#)

</div>

---

## 🚀 About Me

DevOps Engineer with **1.5+ years of hands-on experience** building and automating cloud infrastructure on AWS. I specialise in designing secure, scalable cloud environments — from provisioning infrastructure with Terraform to deploying containerised workloads on Kubernetes (EKS), automating CI/CD pipelines with Jenkins, and setting up full observability with Datadog.

Before moving into DevOps, I worked **2+ years as a MERN Stack Developer** — which gives me a unique edge: I understand both the **dev and ops** side, making me a faster debugger and a better collaborator in cross-functional teams.

- 🔭 Currently: Building DevOps infrastructure on AWS + Kubernetes
- 🌱 Focus: Cloud-native architecture, IaC, and platform engineering
- 💬 Ask me about: AWS, Terraform, Docker, Kubernetes, Jenkins, CI/CD
- 📫 Reach me: ashubanswal1998@gmail.com
- ⚡ Open to: Remote DevOps / Cloud Engineer roles across India

---

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Route53](https://img.shields.io/badge/Route53-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

### ⚙️ DevOps & Automation
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

### 📊 Monitoring & Observability
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### 🐧 OS & Scripting
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### 🔀 Source Control
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

### 💻 Development Background
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

---

## 📂 DevOps Projects

### 🏗️ [aws-3tier-terraform](https://github.com/ashutosh1998github/aws-3tier-terraform)
> **AWS · Terraform · EC2 · VPC · RDS · ALB · IAM**

Production-ready 3-tier AWS architecture provisioned entirely with Terraform modules.
- VPC with public (Web), private (App), and isolated (DB) subnets across 2 AZs
- Auto Scaling Groups with CPU-based scaling policy (scales at 70% CPU)
- ALB with health checks, RDS MySQL with encrypted storage
- IAM roles with least-privilege, SSM Session Manager (no SSH needed)

---

### 🚀 [cicd-jenkins-pipeline](https://github.com/ashutosh1998github/cicd-jenkins-pipeline)
> **Jenkins · Docker · AWS ECR · EC2 · GitHub Actions · Trivy**

End-to-end CI/CD pipeline — zero manual steps from code push to production deploy.
- 10-stage pipeline: Checkout → Lint → Test → Docker Build → Trivy Scan → ECR Push → Deploy → Health Check → Notify
- Multi-stage Dockerfile (60% smaller final image, no devDependencies in prod)
- Branch strategy: `feature/*` → test only | `develop` → staging | `main` → production
- Slack notifications on every build (pass and fail)

---

### ☸️ [kubernetes-eks-deployment](https://github.com/ashutosh1998github/kubernetes-eks-deployment)
> **Kubernetes · AWS EKS · Terraform · Helm · Kustomize · HPA**

Production-grade Kubernetes deployment with zero-downtime rolling updates and auto-scaling.
- Liveness + Readiness + Startup probes on all pods
- HPA auto-scales 2→10 pods based on CPU (70%) and memory (80%)
- Kustomize overlays: dev (1 replica) and prod (3 replicas) from one base
- PodDisruptionBudget ensures minimum availability during cluster upgrades
- EKS cluster provisioned with Terraform, OIDC for IRSA

---

### 📊 [devops-monitoring-datadog](https://github.com/ashutosh1998github/devops-monitoring-datadog)
> **Datadog · Terraform · DaemonSet · Synthetics · Log Pipelines**

Full observability stack — metrics, logs, traces, uptime checks, and alerts as code.
- 8 production monitors (CPU, memory, error rate, latency, pod crashes, RDS, disk)
- Synthetic uptime checks from Mumbai, Singapore, and US every 60 seconds
- Datadog DaemonSet on EKS — 1 agent per node, full cluster visibility
- Log pipelines with Grok parsers, GeoIP enrichment, HTTP status categorisation
- All dashboards and monitors managed via Terraform (Monitoring as Code)

---

## 📈 GitHub Stats

<div align="center">

![Ashutosh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ashutosh1998github&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ashutosh1998github&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=ashutosh1998github&theme=tokyonight&hide_border=true)

</div>

---

## 💼 Work Experience

| Role | Company | Period |
|---|---|---|
| DevOps Engineer | HisanLabs Pvt Ltd | Mar 2025 – Present |
| Software Developer | APLS Web Development | Dec 2023 – Feb 2025 |
| Web Developer Intern | APLS Web Development | May 2023 – Nov 2023 |

---

## 🎓 Education

- **B.Tech in Computer Science** — Shreeyash Pratishtan College of Engineering | CGPA: 8.34
- **Diploma in Computer Technology** — MIT College of Diploma and Polytechnic

---

## 📬 Let's Connect

I'm actively looking for **remote DevOps / Cloud Engineer** roles in India (10–12 LPA+).
If you're hiring or know someone who is — let's talk!

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashutosh-banswal-front-end-developer)
[![Email](https://img.shields.io/badge/Send_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashubanswal1998@gmail.com)

---

<div align="center">
<i>⭐ If you find my projects useful, consider giving them a star — it helps others discover them!</i>
</div>