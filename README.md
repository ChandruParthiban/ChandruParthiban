<div align="center">
<img src="https://capsule-render.vercel.app/api?type=cylinder&height=280&color=0:020617,40:0c1a3a,80:1a3a6e,100:2563eb&text=CHANDRU%20PARTHIBAN&fontSize=46&fontColor=e2e8f0&fontAlignY=45&animation=blinking&desc=%3C%20Full%20Stack%20Developer%20%2F%3E%20%7C%20Cloud%20Native%20%7C%20System%20Design&descSize=17&descAlignY=65&descFontColor=93c5fd&stroke=3b82f6&strokeWidth=2" width="100%"/>
<br/>
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=2500&pause=800&color=38BDF8&center=true&vCenter=true&width=780&lines=_%20Full+Stack+Developer+%7C+Chennai+%F0%9F%87%AE%F0%9F%87%B3;_%20Java+%C2%B7+Kotlin+%C2%B7+TypeScript+%C2%B7+Python;_%20React+%2B+Next.js+%2B+Node.js+Engineer;_%20Docker+%C2%B7+Kubernetes+%C2%B7+AWS+%C2%B7+GCP+%C2%B7+Azure;_%20Building+Systems+That+Scale+%F0%9F%9A%80" alt="Typing SVG"/>
<br/><br/>
Show Image
 
Show Image
 
Show Image
 
Show Image
</div>
<br/>

◈  $ whoami
<br/>
ts/**
 * @author  Chandru Parthiban
 * @role    Full Stack Developer
 * @version 2025.active
 */
class ChandruParthiban extends Developer {

  readonly name     = "Chandru Parthiban";
  readonly role     = "Full Stack Developer";
  readonly location = "Chennai, India 🇮🇳";
  readonly mission  = "Ship clean. Scale hard.";

  stack = {
    languages : ["Java", "Kotlin", "TypeScript", "JavaScript", "Python"],
    frontend  : ["React", "Next.js", "TailwindCSS", "Redux"],
    backend   : ["Node.js", "Express", "Spring Boot"],
    databases : ["PostgreSQL", "MongoDB", "Redis", "MySQL"],
    devops    : ["Docker", "Kubernetes", "GitHub Actions", "Terraform"],
    cloud     : ["AWS", "GCP", "Azure"],
  };

  now() {
    return [
      "🔭 Building: Supermarket Management System",
      "📐 Studying: Distributed Systems",
      "☁️  Exploring: Cloud-Native Architecture",
      "🧠 Practicing: System Design Patterns",
    ];
  }
}
<br/>

◈  $ ls ./tech-stack
<br/>
<div align="center">
<img src="https://skillicons.dev/icons?i=java,kotlin,ts,js,python&perline=5&theme=dark" />
<br/><sub>&nbsp;&nbsp;Java &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Kotlin &nbsp;&nbsp;&nbsp;&nbsp; TypeScript &nbsp;&nbsp; JavaScript &nbsp;&nbsp; Python</sub>
<br/><br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,redux,html,css&perline=6&theme=dark" />
<br/><sub>React &nbsp;&nbsp;&nbsp; Next.js &nbsp;&nbsp;&nbsp; Tailwind &nbsp;&nbsp;&nbsp; Redux &nbsp;&nbsp;&nbsp; HTML &nbsp;&nbsp;&nbsp; CSS</sub>
<br/><br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,spring,postgres,mongodb,redis&perline=6&theme=dark" />
<br/><sub>Node.js &nbsp;&nbsp; Express &nbsp;&nbsp; Spring &nbsp;&nbsp; Postgres &nbsp;&nbsp; MongoDB &nbsp;&nbsp; Redis</sub>
<br/><br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,gcp,azure,githubactions&perline=6&theme=dark" />
<br/><sub>Docker &nbsp;&nbsp; Kubernetes &nbsp;&nbsp; AWS &nbsp;&nbsp;&nbsp; GCP &nbsp;&nbsp;&nbsp; Azure &nbsp;&nbsp; GH Actions</sub>
<br/><br/>
<img src="https://skillicons.dev/icons?i=git,github,linux,vscode,idea,postman&perline=6&theme=dark" />
<br/><sub>Git &nbsp;&nbsp;&nbsp; GitHub &nbsp;&nbsp;&nbsp; Linux &nbsp;&nbsp;&nbsp; VS Code &nbsp;&nbsp; IntelliJ &nbsp;&nbsp; Postman</sub>
</div>
<br/>

◈  $ cat ./stats.json
<br/>
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=ChandruParthiban&show_icons=true&theme=tokyonight&hide_border=true&border_radius=16&count_private=true&include_all_commits=true&rank_icon=github&custom_title=Chandru%27s+GitHub+Stats&icon_color=38bdf8" height="190"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChandruParthiban&theme=tokyonight&hide_border=true&border_radius=16&layout=donut&langs_count=8&custom_title=Language+Breakdown" height="190"/>
</div>
<br/>
<div align="center">
<img src="https://nirzak-streak-stats.vercel.app?user=ChandruParthiban&theme=tokyonight&hide_border=true&border_radius=16&stroke=2563eb&ring=38bdf8&fire=f59e0b&currStreakLabel=38bdf8&sideLabels=93c5fd&dates=475569" width="65%"/>
</div>
<br/>

◈  $ git log --graph
<br/>
<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChandruParthiban&theme=tokyo-night&hide_border=true&radius=16&area=true&point=38bdf8&color=38bdf8&line=2563eb&area_color=1e3a8a" width="97%"/>
</div>
<br/>

◈  $ docker ps -a  — Featured Project
<br/>
<table width="100%">
<tr>
<td width="50%" valign="top">
🛒  Supermarket Management System
yaml# docker-compose.yml (excerpt)
services:
  frontend:
    image: react-next-app
    ports: ["3000:3000"]
    env: [TAILWIND, REDUX]

  backend:
    image: node-express-api
    ports: ["8080:8080"]
    env: [JWT_AUTH, REST_API]

  database:
    image: postgres:15
    volumes: [./data:/var/lib/pg]

  cache:
    image: redis:alpine

  # roadmap:
  #   - kubernetes: planned
  #   - cloud_deploy: planned
Highlights:

✦ Inventory & billing engine
✦ JWT auth + role-based access
✦ Real-time product sync
✦ Clean layered architecture

</td>
<td width="50%" valign="top" align="center">
<br/><br/>
   SYSTEM ARCHITECTURE
   ───────────────────

   ┌──────────┐    ┌──────────┐
   │  React   │───▶│ Next.js  │
   │  (UI)    │    │  (SSR)   │
   └────┬─────┘    └────┬─────┘
        └──────┬────────┘
               ▼
        ┌─────────────┐
        │  Node.js /  │
        │  Express    │◀── REST API
        └──────┬──────┘
        ┌──────┼──────┐
        ▼      ▼      ▼
   ┌────────┐ ┌─────┐ ┌───────┐
   │Postgres│ │Mongo│ │ Redis │
   └────────┘ └─────┘ └───────┘
               ▼
   ┌───────────────────────┐
   │  Docker  ▸  K8s       │
   │  AWS / GCP / Azure    │
   └───────────────────────┘
</td>
</tr>
</table>
<br/>

◈  $ kubectl get achievements
<br/>
<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=ChandruParthiban&theme=tokyonight&no-frame=true&column=7&margin-w=10&margin-h=10" width="97%"/>
</div>
<br/>

◈  $ crontab -l  — Learning Sprint
<br/>
<div align="center">
PriorityTopicStatus🔴 HIGHDistributed Systems & Consensus Algorithmsin-progress🔴 HIGHKubernetes Deep Dive + Helm Chartsin-progress🟡 MEDEvent-Driven Architecture — Kafkaqueued🟡 MEDInfrastructure as Code — Terraformqueued🟢 LOWCloud Security & IAM Best Practicesplanned🟢 LOWService Mesh — Istio & Envoyplanned🟢 LOWSRE Practices & Observabilityplanned
</div>
<br/>

◈  $ snake ./contributions
<br/>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ChandruParthiban/ChandruParthiban/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ChandruParthiban/ChandruParthiban/output/github-contribution-grid-snake.svg"/>
    <img alt="contribution snake" src="https://raw.githubusercontent.com/ChandruParthiban/ChandruParthiban/output/github-contribution-grid-snake.svg"/>
  </picture>
</div>
<div align="center">
<sub>⚙️ One-time setup → <a href="https://github.com/Platane/snk">github.com/Platane/snk</a></sub>
</div>
<br/>

◈  $ fortune | cowsay
<br/>
<div align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="78%"/>
</div>
<br/>

◈  $ ssh connect@chandru
<br/>
<div align="center">
Show Image
 
Show Image
 
Show Image
 
Show Image
<br/><br/>
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   "Good software is not written. It is engineered."          ║
║                                                              ║
║                              — Chandru Parthiban             ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
<br/>
<img src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:020617,40:0c1a3a,80:1a3a6e,100:2563eb" width="100%"/>
</div>
