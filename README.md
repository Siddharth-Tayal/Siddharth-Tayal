<h1 align="center">Siddharth Tayal</h1>

<p align="center">
  <b>Backend systems · Embedded Linux · Applied AI</b><br>
  I work where the web stack meets hardware — production servers that run factory floors,<br>
  flight stacks on companion computers, and real-time pipelines that cannot drop a packet.
</p>

<p align="center">
  <a href="https://linkedin.com/in/siddharthtayal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:stayal12345@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.geeksforgeeks.org/profile/siddharth_tayal"><img src="https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="GeeksforGeeks"></a>
  <a href="https://www.zenithratech.com"><img src="https://img.shields.io/badge/ZenithraTech-1f2937?style=for-the-badge&logoColor=white" alt="Website"></a>
</p>

---

### What I've shipped

**End-of-line production server** — Re-architected a factory EOL server from
legacy HTML bundles to React. The rewrite collapsed the core module from 1,450
to 250 lines, but the point was what it unlocked: the old build hard-coded a
single device (AX1), and the new one treats device type as configuration, so
bringing a new hardware variant onto the line no longer means a new code path.
Runs a multi-vendor production line today.

**GPS-denied navigation** — Brought up the NXP i.MX8M Plus NavQPlus from bare
board: custom Yocto Linux image, on-board AI models, ORB-SLAM and OpenVINS on a
RealSense D435i for visual-inertial odometry. Bridged Gazebo physics to the PX4
flight stack and validated HITL/SITL through to Offboard control.

**Zen AI intent routing** — Intent classification for the Armor Glasses Android
app, resolving spoken input to on-device actions. Fuzzy-matched contact search
across three tiers: offline, online-enriched, and personalized by interaction
frequency.

**Real-time UDP map mirroring** — Low-latency map state synchronization secured
by Zen Authentication, with an IP validation and packet-filtering layer that
authenticates every packet before it reaches the application core.

**Edge AI benchmarking** — Six-week evaluation of the Milk-V Duo for Driver
Monitoring System integration. Benchmarked YOLO detection and face tracking,
documented the hardware's real performance ceiling, and redirected the team away
from an integration that would not have held up.

---

### Projects

| Project | What it is |
|---|---|
| **[Zenith-Shop](https://github.com/Siddharth-Tayal/Zenith-Shop)** | Event-driven microservices e-commerce backend. API gateway with Redis rate limiting, Postgres-backed auth, Mongo-backed catalog with cache-aside reads, Kafka event bus. Mixed persistence on purpose — relational integrity where it matters, document store where it doesn't. |
| **[Chat_App](https://github.com/Siddharth-Tayal/Chat_App)** | MERN real-time messaging over Socket.IO — auth, group chats, instant delivery. JWTs issued as HTTP-only cookies rather than `localStorage`, so an XSS bug isn't an account takeover. |
| **[gesture-detection](https://github.com/Siddharth-Tayal/gesture-detection)** | Real-time hand gesture recognition in the browser with Next.js and TensorFlow.js HandPose. **[Live demo →](https://gesture-detection-kappa.vercel.app)** |
| **[Nexus-Mart](https://github.com/Siddharth-Tayal/Nexus-Mart)** | Full-stack MERN commerce: Stripe payments, Cloudinary uploads, order processing, email notifications. |

I also run a self-hosted Gitea instance on AWS EC2, which is where most of my
opinions about open-source developer infrastructure versus commercial SaaS
come from.

---

### Stack

**Primary** — what I've built production or near-production systems with, and
will happily be interrogated about:

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Embedded%20Linux%20%2F%20Yocto-FCC624?style=flat-square&logo=linux&logoColor=black)
![PX4](https://img.shields.io/badge/PX4%20%2F%20Gazebo-4B0082?style=flat-square&logoColor=white)

**Familiar with** — used in real projects, still learning the sharp edges:
AWS (EC2, S3, ALB) · Apache Kafka · Socket.IO · Flask · Qt · Prisma ·
OpenCV · TensorFlow.js · ORB-SLAM / OpenVINS · Nginx

---

### GitHub

<p align="center">
  <img src="https://img.shields.io/github/followers/Siddharth-Tayal?style=for-the-badge&logo=github&logoColor=white&color=1f2937&labelColor=0d1117" alt="Followers">
  <img src="https://img.shields.io/github/stars/Siddharth-Tayal?style=for-the-badge&logo=github&logoColor=white&color=1f2937&labelColor=0d1117" alt="Stars">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Siddharth-Tayal&hide_border=true&theme=github-dark&card_width=500" alt="Contribution streak">
</p>


---

### Problem solving

<p align="center">
  <a href="https://www.geeksforgeeks.org/profile/siddharth_tayal">
    <img src="https://img.shields.io/badge/Coding%20Score-718-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="Coding score 718">
    <img src="https://img.shields.io/badge/Problems%20Solved-229-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="229 problems solved">
    <img src="https://img.shields.io/badge/Institute%20Rank-%233-FFB300?style=for-the-badge&logoColor=white" alt="Institute rank 3">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hard-19-E5484D?style=flat-square" alt="19 hard">
  <img src="https://img.shields.io/badge/Medium-140-F76808?style=flat-square" alt="140 medium">
  <img src="https://img.shields.io/badge/Easy-55-30A46C?style=flat-square" alt="55 easy">
  <img src="https://img.shields.io/badge/Basic-15-8E8E8E?style=flat-square" alt="15 basic">
</p>

<p align="center">
  <sub><b>#3 at Vaish College of Engineering</b> · 140 Medium and 19 Hard out of 229 solved —
  the distribution is weighted toward the problems that actually take thinking.<br>
  Full profile on <a href="https://www.geeksforgeeks.org/profile/siddharth_tayal">GeeksforGeeks</a>.</sub>
</p>

---

### Beyond code

- **Smart India Hackathon 2024** — won the college-level internal round; led a
  6-person team to first place under a 24-hour constraint
- **Woodpecker Hackathon** — top 100 of 12,000+ national applicants on a backend
  system design brief
- **B.Tech Computer Science**, Vaish College of Engineering (MDU), Rohtak — 2025

---

<p align="center"><sub>SDE-1 at MapMyIndia (ZenithraTech), New Delhi. Reach me by email.</sub></p>
