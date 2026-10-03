<div align="center">

# Nency Chandiramani

### `Software Engineer  •  Java  •  DSA  •  AI / Computer Vision`

I build computer-vision systems with graph-theoretic backbones and IoT products that work end to end.<br>
Preparing for product-based SDE roles.

<br>

<a href="#about"><img src="https://img.shields.io/badge/About-0d1117?style=for-the-badge&labelColor=0d1117&color=58a6ff" alt="About"></a>
<a href="#featured-projects"><img src="https://img.shields.io/badge/Projects-0d1117?style=for-the-badge&labelColor=0d1117&color=a371f7" alt="Projects"></a>
<a href="#competitive-programming"><img src="https://img.shields.io/badge/DSA-0d1117?style=for-the-badge&labelColor=0d1117&color=39d0d8" alt="DSA"></a>
<a href="#achievements"><img src="https://img.shields.io/badge/Achievements-0d1117?style=for-the-badge&labelColor=0d1117&color=58a6ff" alt="Achievements"></a>
<a href="#certifications"><img src="https://img.shields.io/badge/Certifications-0d1117?style=for-the-badge&labelColor=0d1117&color=a371f7" alt="Certifications"></a>
<a href="#connect"><img src="https://img.shields.io/badge/Connect-0d1117?style=for-the-badge&labelColor=0d1117&color=39d0d8" alt="Connect"></a>

<br><br>

<table>
  <tr>
    <td align="center" width="200"><h2>250+</h2><sub>LeetCode problems</sub></td>
    <td align="center" width="200"><h2>1200+</h2><sub>Codeforces rating</sub></td>
    <td align="center" width="200"><h2>8.26</h2><sub>CGPA · BCA, GLA University</sub></td>
    <td align="center" width="200"><h2>3</h2><sub>Hackathon podium finishes</sub></td>
  </tr>
</table>

</div>

---

## About

<table>
  <tr>
    <td width="50%" valign="top">

**Who**<br>
BCA student at GLA University (2024 – 2027), focused on Software Engineering.

**What I build**<br>
Computer-vision pipelines, AI-assisted health products, and embedded / IoT systems.

**Focus areas**<br>
Java · Data Structures & Algorithms · Backend Development · AI/ML · Computer Vision · IoT

</td>
    <td width="50%" valign="top">

**Currently building**

🔹 Java + DSA depth<br>
🔹 Backend development<br>
🔹 AI / Computer Vision projects

</td>
  </tr>
</table>

---

## Tech Stack

<table>
  <tr>
    <td width="170"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=java,py,js,mysql&theme=dark" alt="Java, Python, JavaScript"><br><sub>Java · Python · SQL · JavaScript</sub></td>
  </tr>
  <tr>
    <td><b>AI / Computer Vision</b></td>
    <td><img src="https://skillicons.dev/icons?i=pytorch,opencv,numpy,pandas&theme=dark" alt="PyTorch, OpenCV, NumPy, Pandas"><br><sub>PyTorch · OpenCV · NumPy · Pandas · scikit-image</sub></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=fastapi,nodejs&theme=dark" alt="FastAPI, Node.js"><br><sub>FastAPI · REST APIs · Node.js</sub></td>
  </tr>
  <tr>
    <td><b>Databases</b></td>
    <td><img src="https://skillicons.dev/icons?i=mongodb,mysql&theme=dark" alt="MongoDB, MySQL"><br><sub>MongoDB · MySQL</sub></td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td><img src="https://skillicons.dev/icons?i=git,github&theme=dark" alt="Git, GitHub"><br><sub>Git · GitHub · NetworkX</sub></td>
  </tr>
</table>

---

## Featured Projects

### 🛰️ RoadVision AI &nbsp;<sup>Flagship</sup>

> **Occlusion-Robust Road Extraction & Graph-Theoretic Criticality Analysis for Urban Mobility**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=58a6ff)
![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=a371f7)
![U-Net](https://img.shields.io/badge/U--Net-0d1117?style=flat-square&color=0d1117&labelColor=0d1117&logoColor=39d0d8)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=39d0d8)
![OpenCV](https://img.shields.io/badge/OpenCV-0d1117?style=flat-square&logo=opencv&logoColor=58a6ff)
![NetworkX](https://img.shields.io/badge/NetworkX-0d1117?style=flat-square&color=0d1117&logoColor=a371f7)

**Pipeline**

```text
 Satellite Image ──▶ Preprocessing ──▶ U-Net ──▶ Road Mask ──▶ Skeleton
                                                                  │
 Resilience ◀── Criticality ◀── Graph Healing ◀── Gap Detection ◀─┴─ Graph
```

<table>
  <tr>
    <th align="left">Stage</th>
    <th align="left">What happens</th>
  </tr>
  <tr><td><b>Input</b></td><td>Satellite imagery uploaded through a FastAPI service</td></tr>
  <tr><td><b>Preprocessing</b></td><td>Image preprocessing and tensor normalization</td></tr>
  <tr><td><b>Segmentation</b></td><td>Custom U-Net for pixel-level road masks, evaluated with Dice / IoU</td></tr>
  <tr><td><b>Occlusion-aware training</b></td><td>Synthetic cloud, tree, shadow, and obstacle regions, including road-aware targeted occlusions</td></tr>
  <tr><td><b>Skeletonization</b></td><td>Road mask reduced to a skeleton</td></tr>
  <tr><td><b>Graph construction</b></td><td>8-connected skeleton graph with endpoint, junction, and connected-component detection</td></tr>
  <tr><td><b>Gap detection &amp; healing</b></td><td>Distance and angular alignment, Union-Find (DSU), Kruskal / MST-based connections</td></tr>
  <tr><td><b>Graph analysis</b></td><td>Shortest paths and betweenness centrality to identify critical nodes</td></tr>
  <tr><td><b>Stress testing</b></td><td>Node-failure simulation, connectivity comparison, and alternate-route analysis, returned as JSON</td></tr>
</table>

<br>

<a href="https://github.com/nencycodes/road-extraction-ai"><img src="https://img.shields.io/badge/View_Repository-0d1117?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117&color=58a6ff" alt="RoadVision AI repository"></a>

<br>

---

### 🩺 HealthMate AI

> **AI + IoT health monitoring: reports, vitals, and medication in one product**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=58a6ff)
![AI/ML](https://img.shields.io/badge/AI%2FML-0d1117?style=flat-square&color=0d1117&logoColor=a371f7)
![IoT](https://img.shields.io/badge/IoT-0d1117?style=flat-square&color=0d1117&logoColor=39d0d8)
![Sensors](https://img.shields.io/badge/Sensors-0d1117?style=flat-square&color=0d1117&logoColor=58a6ff)
![I2C](https://img.shields.io/badge/I%C2%B2C-0d1117?style=flat-square&color=0d1117&logoColor=a371f7)

```text
 Medical Reports  ─┐
 Wearable Sensors ─┼──▶  HealthMate AI  ──▶  Analysis · Monitoring · Assistance
 User Interaction ─┘
```

<table>
  <tr>
    <td width="33%" valign="top"><b>Reports &amp; Insights</b><br>OCR-based medical report analysis, symptom interpretation, preventive health insights</td>
    <td width="33%" valign="top"><b>Live Monitoring</b><br>Heart rate, SpO<sub>2</sub>, temperature, and fall detection through wearable integration on a live dashboard</td>
    <td width="33%" valign="top"><b>Assistance</b><br>Real-time AI chatbot using relevant historical user context, plus an emergency-contact workflow</td>
  </tr>
  <tr>
    <td colspan="3"><b>Medicine adherence:</b> scheduling and day-to-day tracking, with reminders on an I²C display and intake confirmed by a physical button</td>
  </tr>
</table>

<a href="https://github.com/nencycodes?tab=repositories"><img src="https://img.shields.io/badge/Browse_Repositories-0d1117?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117&color=a371f7" alt="Repositories"></a>

<br>

---

### ⌚ LifeGuard Band

> **IoT / embedded wearable for continuous monitoring and emergency response**

![IoT](https://img.shields.io/badge/IoT-0d1117?style=flat-square&color=0d1117&logoColor=39d0d8)
![Embedded Systems](https://img.shields.io/badge/Embedded_Systems-0d1117?style=flat-square&color=0d1117&logoColor=58a6ff)
![Sensors](https://img.shields.io/badge/Sensors-0d1117?style=flat-square&color=0d1117&logoColor=a371f7)

A wearable safety prototype built around embedded sensors and a compact hardware interface, with sensor-driven event detection and automated emergency alerts.

---

## Competitive Programming

<div align="center">

<table>
  <tr>
    <td align="center" width="260"><h1>250+</h1><b>LeetCode</b><br><sub>problems solved</sub></td>
    <td align="center" width="260"><h1>1200+</h1><b>Codeforces</b><br><sub>rating</sub></td>
  </tr>
</table>

<a href="https://leetcode.com/u/nencycodes/"><img src="https://img.shields.io/badge/LeetCode_Profile-0d1117?style=for-the-badge&logo=leetcode&logoColor=FFA116&labelColor=0d1117&color=39d0d8" alt="LeetCode"></a>
<a href="https://codeforces.com/profile/NencyChandiramani"><img src="https://img.shields.io/badge/Codeforces_Profile-0d1117?style=for-the-badge&logo=codeforces&logoColor=58a6ff&labelColor=0d1117&color=58a6ff" alt="Codeforces"></a>

</div>

---

## Achievements

<table>
  <tr>
    <td width="60" align="center">🥇</td>
    <td><b>1st Position</b> · CodePunk V2.0</td>
    <td align="right"><sub>HealthMate AI</sub></td>
  </tr>
  <tr>
    <td align="center">🥇</td>
    <td><b>1st Prize</b> · HackVision 2K26</td>
    <td align="right"><sub>HealthMate AI</sub></td>
  </tr>
  <tr>
    <td align="center">🏅</td>
    <td><b>2nd Runner-Up</b> · Technavya Techfest</td>
    <td align="right"><sub>LifeGuard Band</sub></td>
  </tr>
  <tr>
    <td align="center">🏁</td>
    <td><b>Grand Finale Finalist</b> · HackWithUttarPradesh 2025</td>
    <td align="right"><sub>Hackathon</sub></td>
  </tr>
  <tr>
    <td align="center">🏆</td>
    <td><b>Top 25</b> · DEVIATHON National Hackathon</td>
    <td align="right"><sub>Hackathon</sub></td>
  </tr>
  <tr>
    <td align="center">🎨</td>
    <td><b>1st Position</b> · GitHub Logo Design Competition, DEVIATHON</td>
    <td align="right"><sub>Design</sub></td>
  </tr>
</table>

---

## Certifications

<div align="center">

<img src="https://img.shields.io/badge/Microsoft_Certified-Fabric_Analytics_Engineer_Associate_(DP--600)-0d1117?style=for-the-badge&logo=microsoft&logoColor=58a6ff&labelColor=0d1117&color=58a6ff" alt="Microsoft DP-600">
<br>
<img src="https://img.shields.io/badge/MongoDB-Developer_Certification-0d1117?style=for-the-badge&logo=mongodb&logoColor=39d0d8&labelColor=0d1117&color=39d0d8" alt="MongoDB Developer Certification">

</div>

---

## Connect

<div align="center">

<a href="https://www.linkedin.com/in/nency-chandiramani"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff&labelColor=0d1117&color=58a6ff" alt="LinkedIn"></a>
<a href="https://github.com/nencycodes"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117&color=a371f7" alt="GitHub"></a>
<a href="https://leetcode.com/u/nencycodes/"><img src="https://img.shields.io/badge/LeetCode-0d1117?style=for-the-badge&logo=leetcode&logoColor=FFA116&labelColor=0d1117&color=39d0d8" alt="LeetCode"></a>
<a href="https://codeforces.com/profile/NencyChandiramani"><img src="https://img.shields.io/badge/Codeforces-0d1117?style=for-the-badge&logo=codeforces&logoColor=58a6ff&labelColor=0d1117&color=58a6ff" alt="Codeforces"></a>

<br><br>

<sub>Building systems that keep working when the input is imperfect.</sub>

</div>
