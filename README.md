<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:30363d&height=200&section=header&text=John%20Bekele&fontSize=50&fontColor=58a6ff&animation=fadeIn&fontAlignY=35&desc=Cloud%20Architect%20%7C%20Full-Stack%20Developer%20%7C%20Security%20Enthusiast&descSize=16&descAlignY=55&descAlign=50"/>

<p align="center">
  <a href="https://yohansportifolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="mailto:yohansdemisie@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/johnbekele"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=johnbekele&style=for-the-badge&color=0d1117&labelColor=161b22&label=PROFILE+VIEWS"/>
</p>

---

<h2>
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">
  About Me
</h2>

```js
const johnbekele = {
    pronouns: "he" | "him",
    location: "Building in the Cloud",
    code: ["TypeScript", "Python", "JavaScript", "Go"],
    architecture: ["microservices", "serverless", "event-driven"],
    cloud: {
        aws: ["EC2", "Lambda", "ECS", "EKS", "S3", "RDS", "DynamoDB", "CloudFront"],
        iac: ["Terraform", "Pulumi", "CloudFormation"],
        cicd: ["GitHub Actions", "Jenkins", "AWS CodePipeline"]
    },
    currentFocus: "Building visual cloud architecture tools",
    funFact: "I break things to understand how they work, then build them better"
};
```

---

<h2>
  <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28">
  GitHub Analytics
</h2>

<p align="center">
  <a href="https://github.com/johnbekele">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=johnbekele&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9&count_private=true&include_all_commits=true"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=johnbekele&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/johnbekele">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=johnbekele&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=ff7b72&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=58a6ff&sideLabels=8b949e&dates=6e7681"/>
  </a>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=johnbekele&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area=true&area_color=1f6feb"/>
</p>

---

<h2>
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="28">
  Cloud Architecture Projects
</h2>

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">VibeKit - AWS Designer</h3>
<p align="center">
  <a href="https://github.com/johnbekele/swift-UI">
    <img src="https://img.shields.io/badge/Visual_Cloud_Architecture_Designer-0d1117?style=for-the-badge"/>
  </a>
</p>

```
┌─────────────────────────────────────┐
│  ┌─────────┐      ┌─────────┐      │
│  │   VPC   │      │   ALB   │      │
│  │ 10.0.0.0│ ───► │  :443   │      │
│  └─────────┘      └────┬────┘      │
│       │                │           │
│  ┌────┴────┐      ┌────▼────┐      │
│  │ Subnet  │      │   ECS   │      │
│  │ Public  │      │ Fargate │      │
│  └─────────┘      └─────────┘      │
└─────────────────────────────────────┘
        ▼ Generate Code ▼
    [Terraform] [Pulumi]
```

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/React_Flow-FF0072?style=flat-square&logo=react&logoColor=white"/>
</p>

</td>
<td width="50%" valign="top">

<h3 align="center">EKS CI/CD Pipeline</h3>
<p align="center">
  <a href="https://github.com/johnbekele/CI-CD---pulumi--Kubernates-EKS-GithubAction">
    <img src="https://img.shields.io/badge/Kubernetes_on_AWS_EKS-0d1117?style=for-the-badge"/>
  </a>
</p>

```
┌──────────────────────────────────────┐
│         GitHub Actions               │
│  ┌────────┐  ┌────────┐  ┌────────┐ │
│  │  Test  │─►│ Build  │─►│ Deploy │ │
│  └────────┘  └────────┘  └───┬────┘ │
│                              │      │
│  ┌───────────────────────────▼────┐ │
│  │         AWS EKS Cluster        │ │
│  │  ┌─────┐  ┌─────┐  ┌─────┐    │ │
│  │  │ Pod │  │ Pod │  │ Pod │    │ │
│  │  └─────┘  └─────┘  └─────┘    │ │
│  └────────────────────────────────┘ │
└──────────────────────────────────────┘
```

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3 align="center">Wise Trade Platform</h3>
<p align="center">
  <a href="https://github.com/johnbekele/wise-trade-pulumi-deployment">
    <img src="https://img.shields.io/badge/Cloud_Native_Trading_Platform-0d1117?style=for-the-badge"/>
  </a>
</p>

```
┌────────────────────────────────────┐
│   ┌─────────┐    ┌─────────────┐  │
│   │   CDN   │    │ API Gateway │  │
│   └────┬────┘    └──────┬──────┘  │
│        │                │         │
│   ┌────▼────┐    ┌──────▼──────┐  │
│   │   S3    │    │   Lambda    │  │
│   │ Static  │    │  Functions  │  │
│   └─────────┘    └──────┬──────┘  │
│                         │         │
│              ┌──────────▼───────┐ │
│              │    DynamoDB      │ │
│              └──────────────────┘ │
└────────────────────────────────────┘
```

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

</td>
<td width="50%" valign="top">

<h3 align="center">Architecture Expertise</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Cloud_Solutions_Architect-0d1117?style=for-the-badge"/>
</p>

```
┌────────────────────────────────────┐
│                                    │
│    ✓ AWS Well-Architected          │
│    ✓ Infrastructure as Code        │
│    ✓ Serverless Architecture       │
│    ✓ Container Orchestration       │
│    ✓ CI/CD Pipeline Design         │
│    ✓ Security Best Practices       │
│    ✓ Cost Optimization             │
│    ✓ High Availability Design      │
│                                    │
└────────────────────────────────────┘
```

<p align="center">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

</td>
</tr>
</table>

---

<h2>
  <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28">
  Tech Stack
</h2>

<table align="center">
<tr>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=aws" width="48" height="48" alt="AWS" />
<br><b>AWS</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" />
<br><b>Docker</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=kubernetes" width="48" height="48" alt="Kubernetes" />
<br><b>Kubernetes</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=terraform" width="48" height="48" alt="Terraform" />
<br><b>Terraform</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux" />
<br><b>Linux</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=nginx" width="48" height="48" alt="Nginx" />
<br><b>Nginx</b>
</td>
</tr>
<tr>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=ts" width="48" height="48" alt="TypeScript" />
<br><b>TypeScript</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=py" width="48" height="48" alt="Python" />
<br><b>Python</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JavaScript" />
<br><b>JavaScript</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=react" width="48" height="48" alt="React" />
<br><b>React</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=nextjs" width="48" height="48" alt="Next.js" />
<br><b>Next.js</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js" />
<br><b>Node.js</b>
</td>
</tr>
<tr>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=fastapi" width="48" height="48" alt="FastAPI" />
<br><b>FastAPI</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=django" width="48" height="48" alt="Django" />
<br><b>Django</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL" />
<br><b>PostgreSQL</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=mongodb" width="48" height="48" alt="MongoDB" />
<br><b>MongoDB</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis" />
<br><b>Redis</b>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
<br><b>Git</b>
</td>
</tr>
</table>

---

<h2>
  <img src="https://media.giphy.com/media/ZCN6F3FAkwsyOGU2RS/giphy.gif" width="28">
  Trophies
</h2>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=johnbekele&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=15&margin-h=15"/>
</p>

---

<h2>
  <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="28">
  Let's Connect
</h2>

<p align="center">
  <i>Open to collaborating on cloud architecture projects and innovative solutions</i>
</p>

<p align="center">
  <a href="https://yohansportifolio.vercel.app/">
    <img src="https://img.shields.io/badge/Check_Out_My_Portfolio-58a6ff?style=for-the-badge&logo=safari&logoColor=white"/>
  </a>
</p>

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:30363d&height=120&section=footer"/>
