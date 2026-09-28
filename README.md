<div align="center">

# 👋 Hey, I'm **Nabhan Khan**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Computer+Engineering+Student+%F0%9F%92%BB;Python+Developer+%F0%9F%90%8D;Web+Developer+%F0%9F%8C%90;AI+%26+Automation+Enthusiast+%F0%9F%A4%96;Discord+Bot+Developer+%F0%9F%92%AC;Arduino+%26+Embedded+Projects+%E2%9A%A1;Graphic+Designer+%F0%9F%8E%A8;Building+Ideas+Into+Reality+%F0%9F%9A%80" alt="Typing SVG" />

<br>

<img src="https://komarev.com/ghpvc/?username=callmesomeone000&label=PROFILE+VIEWS&color=00F7FF&style=for-the-badge" />

</div>

---

## 🧠 About Me

<img align="right" width="300" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif">

💻 **Computer Engineering Student**

🐍 Python Developer

🌐 Web Developer

🤖 AI & Automation Enthusiast

💬 Discord Bot Developer

⚡ Arduino & Embedded Systems

📊 Data Processing & Visualization

🎨 Graphic Designer

🎬 Video Editing & Digital Content

🔧 I enjoy building projects that combine **software, hardware, AI and creativity**.

🧩 Always experimenting with new technologies and turning ideas into working projects.

<br clear="right"/>

---

# 🛠️ Skills & Technologies

<div align="center">

### 🐍 Programming & Development

<img src="https://skillicons.dev/icons?i=python,html,css,js,mysql" />

<br><br>

### 📊 Python & Data

<img src="https://skillicons.dev/icons?i=python" />

<br>

`NumPy` `Pandas` `Matplotlib` `OpenPyXL` `Tkinter`

<br><br>

### 🤖 AI & Intelligent Systems

`Gemini` `Whisper` `YAMNet` `AI APIs` `Automation`

<br><br>

### 🔌 Hardware & Embedded

<img src="https://skillicons.dev/icons?i=arduino" />

`Arduino` `Sensors` `Embedded Projects`

<br><br>

### 💬 Bots & APIs

`Discord.py` `Discord APIs` `REST APIs` `Python Automation`

<br><br>

### 🌐 Web

<img src="https://skillicons.dev/icons?i=html,css,js" />

<br>

`HTML` `CSS` `JavaScript` `MySQL`

<br><br>

### 🔧 Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode,npm" />

</div>

---

# 🚀 Featured Project

# 🛡️ GUARDIAN

<div align="center">

### *When a person cannot ask for help, Guardian asks for help on their behalf.*

</div>

Guardian is an emergency-response system designed to create an automated response pathway when a person may be unable to manually call for help.

It combines **sensor signals, audio intelligence, location tracking, AI processing and connectivity fallback mechanisms**.

### 🧠 Guardian Technology Stack

```text
Flutter
Python
FastAPI
Firebase
Google Maps
Gemini
Whisper
YAMNet
GPS
PDR
Bluetooth / Wi-Fi Direct
Cellular / SMS
```

> Flutter was used as part of the Guardian project; the mobile-app implementation was handled by another member of the team.

---

## 🔍 How Guardian Works

```text
                    📱 SMARTPHONE
                         │
              ┌──────────┴──────────┐
              │                     │
        📳 SENSOR SIGNALS       🎙️ AUDIO
              │                     │
        IMU / IMPACT             Whisper
        ROTATION                 YAMNet
              │                     │
              └──────────┬──────────┘
                         ↓
                  🧠 UNDERSTAND
                         │
              Multi-Signal Analysis
                         ↓
                    📍 LOCATE
                         │
                 GPS + PDR
                         ↓
                    📡 RELAY
                         │
          ┌──────────────┼──────────────┐
          ↓              ↓              ↓
      Cellular       Bluetooth       Wi-Fi Direct
          │              │              │
          └──────────────┼──────────────┘
                         ↓
                     ☁️ SYNC
                      Firebase
                         ↓
                    🚨 ALERT
                         │
                      Gemini
                         ↓
              📩 Emergency Summary
```

---

## 🎙️ Audio Intelligence

Guardian uses multiple models for different audio tasks:

### 🗣️ Whisper

Used for **speech / voice recognition**, helping identify relevant spoken emergency information.

### 🔊 YAMNet

Used for **environmental sound classification**, helping distinguish relevant sounds from ordinary background audio.

Together, they provide an additional audio-based signal alongside sensor information.

---

## 🧠 AI with Gemini

Guardian uses **Gemini** to process relevant emergency information and help generate a concise emergency summary containing contextual information such as:

📍 Location
🚨 Detected event
🎙️ Relevant audio information
📱 Available emergency context

The generated information can then be used as part of the emergency alert pathway.

---

# 📡 Relay & Connectivity Fallback

Guardian is designed not to depend on a single communication path.

If normal cellular connectivity becomes unavailable, the system can use a **relay mechanism** involving nearby devices.

```text
📱 Guardian Device
       │
       │ No Cellular
       ↓
📡 Nearby Devices
       │
       ├── Bluetooth
       │
       └── Wi-Fi Direct
       │
       ↓
📲 Relay Device
       │
       ↓
🌐 Available Connectivity
       │
       ↓
☁️ Firebase / Emergency System
       │
       ↓
🚨 Alert
```

This creates a potential **device-to-device relay pathway** instead of relying entirely on the originating phone's connection.

---

# ⚙️ Guardian Detection Pipeline

<div align="center">

### **DETECT → UNDERSTAND → LOCATE → RELAY → ALERT**

</div>

### 📳 Detect

Sensor and audio signals are continuously evaluated for potentially significant events.

### 🧠 Understand

Multiple signals and AI-based audio analysis provide additional context.

### 📍 Locate

GPS and positioning mechanisms determine the person's location, with PDR helping in situations where GPS availability is limited.

### 📡 Relay

Connectivity can fall back to nearby-device relay mechanisms when direct communication is unavailable.

### 🚨 Alert

Relevant information is processed and delivered through the emergency response pathway.

---

# 🤖 Discord Development

I build **Python-based Discord bots** using Discord's APIs and libraries.

### Projects include:

🎮 **MatchHub**

Interactive matchmaking system with:

* Game modes
* Regions
* Speed selection
* Interactive buttons
* Discord UI components

---

📋 **Field Report Bot**

A structured reporting system featuring:

* Player information
* Performance scoring
* Multiple evaluation categories
* Comments
* Automated report generation
* Player mentions

---

⚔️ **Conflict of Nations Tools**

Python-based utilities and automation for game-related workflows.

---

# 📊 Python & Data

I work with Python for programming, automation, data processing and application development.

### Libraries & Tools

```text
NumPy
Pandas
Matplotlib
OpenPyXL
Tkinter
Discord.py
```

### Things I build with Python

🐍 Automation

📊 Data analysis

📈 Data visualization

📁 Excel processing

🖥️ GUI applications

🤖 Discord bots

🔌 API integrations

⚙️ Utility tools

---

# 🔌 Arduino & Hardware

I also explore the intersection of **software and hardware** through Arduino and sensor-based projects.

```text
Arduino
   ↓
Sensors
   ↓
Data Collection
   ↓
Python / Processing
   ↓
Analysis
   ↓
Application
```

---

# 🌐 Web Development

I build websites using:

<img src="https://skillicons.dev/icons?i=html,css,js" />

### Skills

`HTML`

`CSS`

`JavaScript`

`MySQL`

`Responsive Web Design`

`Frontend Development`

`Backend Integration`

---

# 🎨 Creative Skills

<div align="center">

🎨 **Graphic Design**
🖥️ **UI Design**
🎬 **Video Editing**
📦 **Branding & Packaging**
📱 **Social Media Design**

</div>

I enjoy combining **design and technology** to create projects that are both functional and visually engaging.

---

# 🧪 Currently Exploring

<div align="center">

```text
🤖 Artificial Intelligence
🧠 Machine Learning
👁️ Computer Vision
⚡ Automation
🔌 Embedded Systems
📡 IoT & Connectivity
🧩 AI Agents
🔬 Robotics
🌐 Advanced Web Development
```

</div>

---

# 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=callmesomeone000&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=callmesomeone000&layout=compact&theme=tokyonight&hide_border=true" />

</div>

---

# 🔥 Contribution Streak

<div align="center">

<img src="https://streak-stats.demolab.com?user=callmesomeone000&theme=tokyonight&hide_border=true" />

</div>

---

# 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/callmesomeone000/callmesomeone000/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Snake" />

</div>

---

# 📈 Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=callmesomeone000&theme=tokyo-night&hide_border=true" />

</div>

---

# 💡 My Approach

<div align="center">

### **Think → Build → Break → Learn → Improve**

<br>

I don't just want to learn technology.

### **I want to build with it. 🚀**

</div>

---

# 🤝 Let's Connect

<div align="center">

<a href="https://github.com/callmesomeone000">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=00F7FF&center=true&vCenter=true&width=600&lines=Thanks+for+visiting!+%F0%9F%91%8B;Let's+build+something+awesome+%F0%9F%9A%80;Code+%E2%80%A2+Create+%E2%80%A2+Innovate+%E2%9A%A1" />

</div>

---

<div align="center">

### ⚡ CODE • CREATE • INNOVATE ⚡

</div>
