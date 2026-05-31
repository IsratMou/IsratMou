<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Israt%20Jahan%20Mou&fontSize=40&fontColor=fff&animation=twinkling&fontAlignY=35&desc=AI%20Researcher%20%7C%20Computer%20Vision%20%7C%20IoT%20Security%20%7C%20Full%20Stack&descSize=15&descAlignY=57&descAlign=50" width="100%"/>
</div>

<p align="center">
  <a href="https://github.com/IsratMou">
    <img src="https://komarev.com/ghpvc/?username=IsratMou&style=for-the-badge&color=blueviolet&label=Profile+Views" />
  </a>
  <a href="https://github.com/IsratMou?tab=followers">
    <img src="https://img.shields.io/github/followers/IsratMou?style=for-the-badge&color=blue&label=Followers" />
  </a>
  <a href="https://huggingface.co/MOUcat">
    <img src="https://img.shields.io/badge/🤗%20HuggingFace-MOUcat-FFD21E?style=for-the-badge" />
  </a>
</p>

<p align="center">
  🎓 CSE Undergraduate &nbsp;·&nbsp; 🤖 ML Researcher &nbsp;·&nbsp; 🔒 IoT Security &nbsp;·&nbsp; 🌐 Web Developer
  <br/>
  <em>Building lightweight AI that protects the physical world — even on $2 hardware.</em>
</p>

---

## 🏆 Featured Research Project

<table>
<tr>
<td width="58%" valign="top">

### 🔒 MOI-Lite + E-SATF — IoT Intrusion Detection System
> A **37K-parameter** neural IDS that fits inside an Arduino MCU and still beats larger models.

**Hierarchical pipeline on TON-IoT dataset:**

| Metric | Result |
|---|---|
| 🎯 Binary F1 (Normal vs Attack) | **99.79%** |
| 🏷️ Multiclass Macro F1 (9 classes) | **94.37%** |
| 💾 Size after INT8 Quantization | **65 KB** |
| 📉 Fewer params vs DNN/CNN | **−36.5%** |
| 🛡️ FGSM Adversarial Robustness | **+26% gain** |
| 📊 Statistical equivalence | McNemar p > 0.05 |

**Innovations:**
- 🧠 **E-SATF** — Explanation-Stability-Aware Training (SHAP Top-K Jaccard)
- 🔁 **2-Stage Pipeline** — Binary detection → 9-class attack classification
- ⚡ **INT8 Quantization** → 65 KB for edge/IoT deployment
- 🔬 Adversarial robustness against FGSM attacks

[![Live Demo](https://img.shields.io/badge/🤗%20Live%20Demo-HuggingFace-FF9D00?style=for-the-badge)](https://huggingface.co/spaces/MOUcat/iot-intrusion-detection-dashboard)
[![Repo](https://img.shields.io/badge/GitHub-IDS--moi-181717?style=for-the-badge&logo=github)](https://github.com/IsratMou/IDS-moi)

</td>
<td width="42%" valign="top" align="center">

```
   IoT Network Traffic
          │
          ▼
  ┌───────────────────┐
  │  Stage 1: Binary  │ ← 99.79% F1
  │  Normal vs Attack │
  └────────┬──────────┘
           │ Attack Detected
           ▼
  ┌───────────────────┐
  │  Stage 2: Multi   │ ← 94.37% F1
  │  9 Attack Types   │
  │  DoS·Scanning·    │
  │  Injection·etc    │
  └────────┬──────────┘
           │
    ┌──────┴──────┐
    │  SHAP XAI   │
    │  + INT8     │
    │  → 65 KB    │
    │  → Arduino  │
    └─────────────┘
```

**Stack:** TensorFlow · SHAP · Pandas
**Dataset:** TON-IoT Network
**Platform:** Kaggle → HuggingFace

</td>
</tr>
</table>

---

## 🚀 All Projects

### 🖥️ Web & Full Stack

<table>
<tr>
<td align="center" width="50%" valign="top">

#### 🌐 [Portfolio](https://github.com/IsratMou/Portfolio)
Personal developer portfolio website

![CSS](https://img.shields.io/badge/CSS-53%25-1572B6?style=flat-square&logo=css3)
![HTML](https://img.shields.io/badge/HTML-25%25-E34F26?style=flat-square&logo=html5)
![JS](https://img.shields.io/badge/JavaScript-22%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Built with vanilla CSS + JS + React (portfolio-react folder)
Clean animations · Responsive layout · Project showcase

[→ View Repo](https://github.com/IsratMou/Portfolio)

</td>
<td align="center" width="50%" valign="top">

#### 🤝 [ProtisrutiNgo](https://github.com/IsratMou/ProtisrutiNgo)
NGO website — "প্রতিশ্রুতি" (Protisruti = Promise)

![Python](https://img.shields.io/badge/Python-96%25-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-4%25-E34F26?style=flat-square&logo=html5)

Full-stack NGO platform built with Python + HTML
⭐ 1 star · Community-focused web application

[→ View Repo](https://github.com/IsratMou/ProtisrutiNgo)

</td>
</tr>
</table>

---

### 🤖 AI & Computer Vision

<table>
<tr>
<td align="center" width="50%" valign="top">

#### 🌀 [AI Rasengan: Chakra Control](https://github.com/IsratMou/hand_particles_rasengun)
Real-time hand tracking + 3D Rasengan in the browser

![HTML](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=flat-square&logo=html5)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-FF6F00?style=flat-square&logo=google)
![JS](https://img.shields.io/badge/Vanilla-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

✊ Fist → Charge &nbsp;&nbsp; 🖐 Open → Fire!
✌ Dual hands → Overcharge mode
60 FPS · No WebGL · Pure trigonometry

[→ View Repo](https://github.com/IsratMou/hand_particles_rasengun)

</td>
<td align="center" width="50%" valign="top">

#### 🖐 Hand Particle Experience
60fps skeletal tracking with physics particles

![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Skeleton-FF6F00?style=flat-square&logo=google)
![Canvas](https://img.shields.io/badge/Canvas2D-Glow%20FX-E34F26?style=flat-square)

Drag · Pinch · Hold · Scatter gestures
Screen-blend glow · Trail ring buffer
Velocity-based force physics

[→ View Repo](https://github.com/IsratMou)

</td>
</tr>
</table>

---

### 📚 Learning & Practice

<table>
<tr>
<td align="center" width="50%" valign="top">

#### 🐍 [python-100](https://github.com/IsratMou/python-100)
Python mastery journey — 100 problems

![Python](https://img.shields.io/badge/Python-79%25-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-21%25-F37626?style=flat-square&logo=jupyter&logoColor=white)

`basic syntax` · `loops` · `strings` · `lists`
`DSA / stack` · `PACER python` · `Jupyter notebooks`
27 commits of consistent practice 💪

[→ View Repo](https://github.com/IsratMou/python-100)

</td>
<td align="center" width="50%" valign="top">

#### 🗄️ [SQL-Practice](https://github.com/IsratMou/SQL-Practice)
SQL fundamentals & query practice

![SQL](https://img.shields.io/badge/SQL-Database-4479A1?style=flat-square&logo=mysql&logoColor=white)

DDL · DML · SELECT queries
JOIN operations · Aggregation
Building strong database foundations

[→ View Repo](https://github.com/IsratMou/SQL-Practice)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<p align="center">
  <strong>AI / ML</strong><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/SHAP-XAI-ff6b6b?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
</p>

<p align="center">
  <strong>Computer Vision & Frontend</strong><br/>
  <img src="https://img.shields.io/badge/MediaPipe-FF6F00?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
</p>

<p align="center">
  <strong>Tools & Platforms</strong><br/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
</p>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=IsratMou&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=38bdf8&text_color=e2e8f0&rank_icon=github&include_all_commits=true&count_private=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IsratMou&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=e2e8f0&langs_count=8" height="170"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=IsratMou&theme=tokyonight&hide_border=true&background=0d1117&ring=a78bfa&fire=38bdf8&currStreakLabel=e2e8f0" width="56%"/>
</div>

---

## 🎯 About Me

```python
class IsratMou:
    def __init__(self):
        self.name        = "Israt Jahan Mou"
        self.role        = "CSE Undergraduate"
        self.interests   = ["Lightweight Neural Networks", "IoT Security",
                            "Explainable AI", "Computer Vision", "Web Dev"]
        self.research    = "MOI-Lite: 37K-param IDS that fits in 65 KB"
        self.languages   = ["Python", "JavaScript", "SQL", "HTML/CSS"]
        self.tools       = ["TensorFlow", "MediaPipe", "Kaggle", "HuggingFace"]
        self.fun_fact    = "I squeezed a full IDS into 65 KB 💾 — smaller than a JPEG"

    def current_focus(self):
        return [
            "📖 Finishing CSE degree",
            "🔬 Publishing IDS research",
            "🌐 Building portfolio & web apps",
            "🐍 Mastering Python & DSA",
        ]

    def mission(self):
        return "AI that protects the physical world — even on $2 hardware. 🌍"

me = IsratMou()
print(me.mission())
# → "AI that protects the physical world — even on $2 hardware. 🌍"
```

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://github.com/IsratMou">
    <img src="https://img.shields.io/badge/GitHub-IsratMou-181717?style=for-the-badge&logo=github"/>
  </a>
  &nbsp;
  <a href="https://huggingface.co/MOUcat">
    <img src="https://img.shields.io/badge/🤗%20HuggingFace-MOUcat-FFD21E?style=for-the-badge"/>
  </a>
  &nbsp;
  <a href="https://isratmou.github.io/Portfolio">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20Site-a78bfa?style=for-the-badge&logo=googlechrome&logoColor=white"/>
  </a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
