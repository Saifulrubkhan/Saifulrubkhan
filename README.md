<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=Hi%2C+I'm+Saiful+Khan+%F0%9F%91%8B;Solution+Architect+%7C+Senior+SRE;Building+secure%2C+scalable+cloud+systems" alt="Typing SVG" />

# Saiful Khan

### Solution Architect · Senior DevOps / SRE · Cloud Architect

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-khansaiful.com-0ea5e9?style=for-the-badge&labelColor=0f172a)](https://khansaiful.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saiful-khan-29810426b/)
[![GitHub](https://img.shields.io/badge/GitHub-@Saifulrubkhan-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Saifulrubkhan)
[![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=232F3E)](https://khansaiful.com)

<br/>

<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900" alt="AWS"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>

</div>

---

## About Me

I design and deliver **production cloud platforms** — identity & access, edge delivery, CI/CD, and serverless data paths — with a focus on security, operability, and cost.

My portfolio site **[khansaiful.com](https://khansaiful.com)** is a live AWS Cloud Resume Challenge build (not a static brochure): hosting, HTTPS, DNS, serverless APIs, and automated deploys.

- 🔭 Cloud architecture, platform engineering, and reliable delivery pipelines
- 🌐 Live portfolio: **[khansaiful.com](https://khansaiful.com)**
- 🛠️ AWS · Azure · Kubernetes · Terraform · GitHub Actions · Python
- 📌 Open to **Solutions Architect**, **Senior DevOps/SRE**, and cloud engineering roles

---

## Live architecture — [khansaiful.com](https://khansaiful.com)

```mermaid
flowchart LR
  user([User]) --> r53[Route 53]
  r53 --> cf[CloudFront + ACM]
  cf --> s3[S3 static site]
  user --> api[API Gateway]
  api --> lambda[Lambda]
  lambda --> ddb[(DynamoDB)]
  dev([Developer]) --> gh[GitHub]
  gh --> gha[Actions + OIDC]
  gha --> s3
  gha --> cf
```

| Layer | What it does |
|---|---|
| **Edge** | Route 53 → CloudFront + ACM → S3 (OAC, HTTPS) |
| **Serverless** | API Gateway → Lambda → DynamoDB (visitor count + contact) |
| **Delivery** | GitHub Actions + OIDC → S3 sync + CloudFront invalidation |
| **Next** | Terraform IaC migration **in progress** |

[![Live Site](https://img.shields.io/badge/Live_Site-khansaiful.com-22c55e?style=for-the-badge&logo=vercel&logoColor=white&labelColor=14532d)](https://khansaiful.com)
[![Website Repo](https://img.shields.io/badge/Repo-Saiful_CloudResumeWebsite-181717?style=for-the-badge&logo=github)](https://github.com/Saifulrubkhan/Saiful_CloudResumeWebsite)
[![Visitor API](https://img.shields.io/badge/Repo-Cloud--Resume--Backend-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=232F3E)](https://github.com/Saifulrubkhan/Cloud-Resume-Backend)
[![Contact API](https://img.shields.io/badge/Repo-cloud--resume--api-7C3AED?style=for-the-badge&logo=amazonapigateway&logoColor=white)](https://github.com/Saifulrubkhan/cloud-resume-api)

---

## Experience & strengths

<table>
<tr>
<td width="50%" valign="top">

### 🧭 What I build

- Secure AWS / Azure architectures for scalable systems  
- CI/CD and automation across environments  
- Kubernetes, Docker, and cloud-native platform design  
- Platform engineering with operational excellence  

</td>
<td width="50%" valign="top">

### 💪 How I work

- Architecture trade-offs: security, cost, reliability  
- Least-privilege IAM, OIDC federation, edge hardening  
- Serverless APIs and event-driven patterns  
- Clear docs so systems stay operable after go-live  

</td>
</tr>
</table>

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### ☁️ AWS Cloud Resume Challenge
**[khansaiful.com](https://khansaiful.com)**

Production portfolio: Vite → S3/CloudFront, Route 53, Lambda visitor counter, contact API, GitHub Actions OIDC.

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-8C4FFF?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

[Open live site →](https://khansaiful.com)

</td>
<td width="50%" valign="top">

### 🌐 Multi-Region AWS Deployment

Resilient traffic distribution and failover patterns across regions.

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![HA](https://img.shields.io/badge/High_Availability-22c55e?style=flat-square)

[View project →](https://nextwork.ai/radiant_cyan_daring_clementine/docs/596362ad-0e33-40be-95a1-8f2b201dd44e)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Amazon EKS Backend

Containerized workloads on Kubernetes with secure AWS integration.

![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white)
![K8s](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[View project →](https://github.com/Saifulrubkhan/aws-cloud-projects/blob/main/05-containers-compute/29-k8s-backend/aws-compute-eks4.md)

</td>
<td width="50%" valign="top">

### 🤖 AI Agent Application

Full-stack AI app (Spring AI + Angular) for documents and automation workflows.

![Spring](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat-square)

[View project →](https://github.com/Saifulrubkhan/ai-agent-spring-boot-angular.git)

</td>
</tr>
</table>

---

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,gcp,kubernetes,docker,terraform,linux,githubactions,jenkins,python,java,git&theme=dark" alt="Tech stack icons" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" alt="SonarQube"/>
  <img src="https://img.shields.io/badge/JFrog-Artifactory-41BF47?style=for-the-badge&logo=jfrog&logoColor=white" alt="JFrog"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/>
</p>

---

## Certifications

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=232F3E" alt="AWS SAA"/>
  <img src="https://img.shields.io/badge/AWS-AI_Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=232F3E" alt="AWS AI"/>
  <img src="https://img.shields.io/badge/KCNA-Cloud_Native-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="KCNA"/>
  <img src="https://img.shields.io/badge/Cisco-CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" alt="CCNA"/>
</p>

<p align="center">
  📄 More on my resume → <a href="https://khansaiful.com/resume.html"><b>khansaiful.com/resume.html</b></a>
</p>

---

## GitHub snapshot

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Saifulrubkhan&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=F472B6&text_color=E5E7EB&count_private=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Saifulrubkhan&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=E5E7EB" alt="Top languages" />
</div>

<div align="center">
  <br/>
  <img src="https://streak-stats.demolab.com?user=Saifulrubkhan&theme=radical&hide_border=true&background=0D1117" alt="GitHub streak" />
</div>

---

## Let’s connect

<div align="center">

Looking for a Solutions Architect or Senior DevOps/SRE who can design cloud systems, automate delivery, and keep platforms production-ready? Let’s talk.

[![Portfolio](https://img.shields.io/badge/🌐_khansaiful.com-0ea5e9?style=for-the-badge&labelColor=0f172a)](https://khansaiful.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saiful-khan-29810426b/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rubsaiful@gmail.com)

<br/>

**Build once. Operate safely. Improve continuously.**

</div>
