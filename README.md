<p align="center">
  <img src="./assets/title.svg" alt="Hari Hara Babu Saripalli" width="100%"/>
</p>

<p align="center">
  <a href="https://harihara5.github.io/HARI-HARA/"><img src="./assets/swarm-3d.gif" alt="Real-time 3D render: a heterogeneous drone and ground-robot swarm inspects a nuclear site" width="100%"/></a>
</p>
<p align="center">
  <sub>▲ live WebGL render · 8 drones + 4 ground robots · no GPS · cross-modal defect handoff · federated learning · spoof defense</sub>
</p>

<p align="center">
  <!-- LinkedIn / Scholar / ORCID / Email badges go here once links are in -->
  <img src="https://komarev.com/ghpvc/?username=harihara5&label=RADAR%20CONTACTS&color=22d3ee&style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=22D3EE&center=true&vCenter=true&width=820&lines=Drones+that+see+through+concrete+%F0%9F%93%A1;Swarms+that+fly+where+GPS+doesn't+%F0%9F%9B%B0%EF%B8%8F;LiDAR+%C2%B7+GPR+%C2%B7+HSI+%C2%B7+Thermal+%C2%B7+Rad+%C2%B7+Acoustic+%F0%9F%A7%A0;VLM+agents+that+decide+what+to+inspect+next+%F0%9F%A4%96" alt="typing intro"/>
</p>

<p align="center">
  <a href="https://harihara5.github.io/HARI-HARA/"><img src="./assets/enter.svg" alt="Enter Mission Control: interactive 3D site" width="420"/></a>
</p>

<img src="./assets/divider.svg" width="100%"/>

## 🛰️ `> boot sequence`

<p align="center">
  <img src="./assets/terminal.svg" alt="Terminal intro" width="100%"/>
</p>

<img src="./assets/divider.svg" width="100%"/>

## 🧠 `> how my drones think`

<p align="center">
  <img src="./assets/fusion.svg" alt="LiDAR, GPR and hyperspectral data fused into a defect map" width="100%"/>
</p>

Different sensors, different views of the same wall. **LiDAR** maps the surface geometry, **Ground Penetrating Radar** looks *inside* the concrete for rebar and voids, and **hyperspectral imaging** reads chemistry the human eye can't see. Fuse them, and you get a defect map no single sensor could produce. Then a **vision-language agent** reads that map and decides where the swarm flies next.

<img src="./assets/divider.svg" width="100%"/>

## 🗺️ `> dissertation flight plan`

```mermaid
%%{init: {'theme':'dark', 'themeVariables': { 'primaryColor':'#0b1220','primaryTextColor':'#e2e8f0','primaryBorderColor':'#22d3ee','lineColor':'#a855f7','fontFamily':'monospace'}}}%%
flowchart LR
    A["📡 Multi-Sensor<br/>NDE Fusion"] --> D
    B["🧭 GPS-Denied<br/>Autonomous Navigation"] --> D
    C["🤖 LLM / VLM<br/>Agentic Inspection"] --> D
    D{{"🚁🚁🚁<br/>Autonomous Swarm<br/>with Sensor Payloads"}} --> E["🏗️ Critical Infrastructure<br/>Assessment"]
```

<img src="./assets/divider.svg" width="100%"/>

## 🔬 `> active missions`

<table>
<tr>
<td width="50%" valign="top">

### 📡 Multi-Sensor NDE Fusion
LiDAR + GPR + hyperspectral fusion for finding what's wrong *inside* concrete, not just on it.

`Python` `MATLAB` `Deep Learning`

</td>
<td width="50%" valign="top">

### 🐝 Drone Swarm Autonomy
VLM-driven coordination and federated fusion so a team of drones splits the job and shares what it learns.

`Swarm` `VLM` `Simulation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🦎 Hybrid UAS + UGV Wall Drone
One platform that flies, drives on the ground, and **sticks to walls and ceilings** using thrust adhesion.

`Hardware` `Control` `Prototype`

</td>
<td width="50%" valign="top">

### 🌈 Hyperspectral Mapping
Spectral signatures from 400 to 1000 nm turned into material and damage maps.

`HSI` `Computer Vision` `Remote Sensing`

</td>
</tr>
</table>

> 🔒 Code lives in private repos while papers are under review. Ask and I'm happy to talk shop.

<img src="./assets/divider.svg" width="100%"/>

## 📚 `> flight log: publications`

| | Venue | Work | Status |
|:-:|---|---|:-:|
| 🛡️ | ![MDPI](https://img.shields.io/badge/MDPI-Future_Internet-4F5671?style=flat-square) | **PRAHARI**: drones as calibrated aerial trust anchors for radiological IoT sensor networks | ![](https://img.shields.io/badge/accepted-2026-4be39b?style=flat-square) |
| ⚔️ | ![EAI](https://img.shields.io/badge/EAI-ICDF2C-6b7280?style=flat-square) | Impact of cyber attacks on autonomous drone inspection of containment structures | ![](https://img.shields.io/badge/accepted-4be39b?style=flat-square) |
| 📡 | ![IEEE](https://img.shields.io/badge/IEEE-Sensors_Journal-00629B?style=flat-square&logo=ieee&logoColor=white) | Physics-based simulation framework for benchmarking LiDAR + GPR fusion | ![](https://img.shields.io/badge/published-3ee0f0?style=flat-square) |
| 🛰️ | ![MDPI](https://img.shields.io/badge/MDPI-Future_Internet-4F5671?style=flat-square) | LSTM-VAE detection of anomalous drone trajectories | ![](https://img.shields.io/badge/published-3ee0f0?style=flat-square) |

<details>
<summary><b>📖 Book chapters, conference papers & more in the pipeline</b> (click to expand)</summary>
<br/>

- *Add here*

</details>

<img src="./assets/divider.svg" width="100%"/>

## 🛠️ `> payload manifest`

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,matlab,bash,linux,raspberrypi,ros,pytorch,opencv,git,vscode,latex&perline=6" alt="tech stack"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Deep_Learning-0b1220?style=for-the-badge&color=3ee0f0"/>
  <img src="https://img.shields.io/badge/Generative_AI-0b1220?style=for-the-badge&color=ffb547"/>
  <img src="https://img.shields.io/badge/Agentic_AI_(LLM%2FVLM)-0b1220?style=for-the-badge&color=a98bff"/>
  <img src="https://img.shields.io/badge/Federated_Learning-0b1220?style=for-the-badge&color=5ef2c5"/>
  <img src="https://img.shields.io/badge/Edge_AI-0b1220?style=for-the-badge&color=4be39b"/>
  <img src="https://img.shields.io/badge/Cyber_Security-0b1220?style=for-the-badge&color=ff4d6a"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LiDAR-0b1220?style=for-the-badge&color=22d3ee"/>
  <img src="https://img.shields.io/badge/Ground_Penetrating_Radar-0b1220?style=for-the-badge&color=a78bfa"/>
  <img src="https://img.shields.io/badge/Hyperspectral-0b1220?style=for-the-badge&color=facc15"/>
  <img src="https://img.shields.io/badge/Thermal_IR-0b1220?style=for-the-badge&color=ff6a3d"/>
  <img src="https://img.shields.io/badge/Gamma_%2B_Neutron-0b1220?style=for-the-badge&color=9dff4a"/>
  <img src="https://img.shields.io/badge/Acoustic_Beacons-0b1220?style=for-the-badge&color=5ef2c5"/>
  <img src="https://img.shields.io/badge/RGB--D-0b1220?style=for-the-badge&color=e2e8f0"/>
  <img src="https://img.shields.io/badge/Ultrasonic-0b1220?style=for-the-badge&color=a78bfa"/>
  <img src="https://img.shields.io/badge/PX4-0b1220?style=for-the-badge&color=0B5394"/>
  <img src="https://img.shields.io/badge/ArduPilot-0b1220?style=for-the-badge&color=64748b"/>
  <img src="https://img.shields.io/badge/Gazebo-0b1220?style=for-the-badge&color=F58113"/>
  <img src="https://img.shields.io/badge/Hugging_Face-0b1220?style=for-the-badge&logo=huggingface&color=FFD21E"/>
</p>

<img src="./assets/divider.svg" width="100%"/>

## 📊 `> telemetry`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=harihara5&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee&icon_color=a855f7"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harihara5&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=harihara5&theme=tokyonight&hide_border=true&background=0b1220&ring=22d3ee&fire=f43f5e&currStreakLabel=22d3ee"/>
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=harihara5&bg_color=0b1220&color=22d3ee&line=a855f7&point=f0abfc&area=true&area_color=22d3ee&hide_border=true" width="100%"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harihara5/HARI-HARA/output/github-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/harihara5/HARI-HARA/output/github-snake.svg" alt="snake eating my contribution graph"/>
  </picture>
</p>

<img src="./assets/divider.svg" width="100%"/>

<p align="center">
  <code>if (too_dangerous_for_humans) send(drone); if (too_big_for_one) send(swarm);</code>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1a2e,50:1e1035,100:030712&height=110&section=footer&text=signal%20lost...%20returning%20to%20base&fontSize=16&fontColor=64748b&fontAlignY=70"/>
</p>
