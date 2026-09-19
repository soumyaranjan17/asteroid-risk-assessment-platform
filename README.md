
<div align="center">

# ☄️ Asteroid Risk Assessment Platform

### Real-Time Asteroid Intelligence, Risk Analysis & 3D Orbital Visualization

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=4F46E5&center=true&vCenter=true&width=750&lines=Asteroid+Intelligence+Platform;Real-Time+Asteroid+Data;Multi-Factor+Risk+Assessment;Interactive+3D+Orbital+Visualization;React+%7C+Node.js+%7C+Three.js+%7C+WebGL" alt="Typing SVG" />

<br>

<p>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Vite-Build%20Tool-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
  <img src="https://img.shields.io/badge/Three.js-3D-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js"/>
  <img src="https://img.shields.io/badge/WebGL-Visualization-990000?style=for-the-badge&logo=webgl&logoColor=white" alt="WebGL"/>
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-API-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js"/>
</p>

<p>
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/REST%20API-Integration-2563EB?style=for-the-badge" alt="REST API"/>
  <img src="https://img.shields.io/badge/IIT-Hackathon%202026-7C3AED?style=for-the-badge" alt="IIT Hackathon"/>
</p>

<br>

**A full-stack web platform for asteroid tracking, risk assessment, orbital analysis, and immersive 3D visualization.**

<br>

[🚀 Getting Started](#-getting-started) •
[✨ Features](#-key-features) •
[🏗️ Architecture](#️-system-architecture) •
[🌌 3D Visualization](#-3d-visualization) •
[⚠️ Risk Engine](#️-risk-assessment-engine) •
[🗺️ Roadmap](#-roadmap)

</div>

---

# 🌌 Project Overview

**Asteroid Risk Assessment Platform** is a full-stack web application designed to transform asteroid data into an interactive intelligence and visualization experience.

The platform combines:

* 🌍 Real-time asteroid data
* ⚠️ Multi-factor risk assessment
* 🌌 Interactive 3D celestial visualization
* 🛰️ Orbital path visualization
* 📊 Statistical analysis
* 🔐 User authentication
* 🎨 Responsive and animated user interface

Instead of presenting asteroid information as static data, the platform provides an **interactive environment for exploring asteroid characteristics, risk factors, statistics, and orbital behavior**.

---

# 💡 Why This Project?

Asteroid datasets contain large amounts of information about celestial objects, but raw data can be difficult to understand.

This project focuses on transforming that information into:

```text
Raw Asteroid Data
       │
       ▼
┌─────────────────────┐
│ Data Processing     │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Risk Assessment     │
│ Engine              │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Interactive 3D      │
│ Visualization       │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Dashboard & Insights│
└─────────────────────┘
```

The result is a more visual and interactive way to explore asteroid intelligence.

---

# ✨ Key Features

<table>
<tr>
<td width="50%">

### 🌌 3D Visualization

* Interactive asteroid rendering
* 3D celestial objects
* Orbital path visualization
* Camera controls
* Animated space environment
* WebGL-powered graphics

</td>

<td width="50%">

### ⚠️ Risk Assessment

* Multi-factor risk calculation
* Risk scoring
* Asteroid analysis
* Historical data consideration
* Risk categorization

</td>
</tr>

<tr>
<td width="50%">

### 🛰️ Data Integration

* External API integration
* Real-time asteroid information
* Data processing
* Validation
* API service layer
* Response caching

</td>

<td width="50%">

### 📊 Analytics Dashboard

* Asteroid statistics
* Data insights
* Interactive cards
* Dashboard metrics
* Real-time information display

</td>
</tr>

<tr>
<td width="50%">

### 🔐 Authentication

* User registration
* Login system
* Authentication utilities
* Personalized dashboard experience

</td>

<td width="50%">

### 🎨 Modern UI

* Responsive design
* Animated backgrounds
* Interactive components
* Dynamic star field
* Modern dashboard interface

</td>
</tr>
</table>

---

# 🎬 Platform Experience

<div align="center">

### ☄️ Explore → Analyze → Visualize → Assess

```text
          🛰️ ASTEROID DATA
                 │
                 ▼
        ┌──────────────────┐
        │   DATA ENGINE    │
        └────────┬─────────┘
                 │
        ┌────────┴─────────┐
        ▼                  ▼
 ┌─────────────┐    ┌─────────────┐
 │ 3D ENGINE   │    │ RISK ENGINE │
 │ Three.js    │    │ Assessment  │
 └──────┬──────┘    └──────┬──────┘
        │                  │
        └────────┬─────────┘
                 ▼
        ┌──────────────────┐
        │    DASHBOARD     │
        ├──────────────────┤
        │ 📊 Statistics    │
        │ 🌌 Visualization │
        │ ⚠️ Risk Analysis │
        │ 🛰️ Tracking      │
        └──────────────────┘
```

</div>

> **Recommended:** Add screenshots or a short GIF of your actual dashboard and 3D visualization here.

Example:

```markdown
![Dashboard](assets/dashboard.png)

![3D Visualization](assets/3d-visualization.gif)
```

---

# 🏗️ System Architecture

The application follows a full-stack architecture separating the presentation layer, API layer, business logic, and external data services.

```text
                         ┌─────────────────────┐
                         │     External API    │
                         │  Asteroid Data      │
                         └──────────┬──────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────┐
│                     BACKEND                        │
│                                                    │
│  ┌────────────┐    ┌──────────────┐               │
│  │   Routes   │───▶│ Controllers  │               │
│  └────────────┘    └──────┬───────┘               │
│                           │                        │
│                    ┌──────┴───────┐                │
│                    ▼              ▼                │
│             ┌────────────┐ ┌──────────────┐       │
│             │ External   │ │ Risk Engine  │       │
│             │ API Service│ │ Service      │       │
│             └────────────┘ └──────────────┘       │
│                                                    │
└───────────────────────┬────────────────────────────┘
                        │ REST API
                        ▼
┌────────────────────────────────────────────────────┐
│                     FRONTEND                       │
│                                                    │
│  React 18 + Vite + React Router                    │
│                                                    │
│  ┌──────────────┐  ┌──────────────┐               │
│  │ Dashboard    │  │ Authentication│               │
│  └──────────────┘  └──────────────┘               │
│                                                    │
│  ┌──────────────────────────────────────────────┐  │
│  │           Three.js / WebGL Engine            │  │
│  │                                              │  │
│  │ Asteroids • Planets • Stars • Orbits         │  │
│  └──────────────────────────────────────────────┘  │
│                                                    │
└────────────────────────────────────────────────────┘
```

---

# 🧩 Technology Stack

## Frontend

| Technology          | Purpose                       |
| ------------------- | ----------------------------- |
| ⚛️ **React 18**     | UI development                |
| ⚡ **Vite**          | Development and build tooling |
| 🌌 **Three.js**     | 3D rendering                  |
| 🖥️ **WebGL**       | Hardware-accelerated graphics |
| 🧭 **React Router** | Client-side routing           |
| 🎨 **CSS3**         | Styling and animations        |
| 🪝 **React Hooks**  | State and component logic     |
| 🔍 **ESLint**       | Code quality                  |

---

## Backend

| Technology                   | Purpose                       |
| ---------------------------- | ----------------------------- |
| 🟢 **Node.js**               | Server runtime                |
| 🚂 **Express.js**            | REST API framework            |
| 🏗️ **MVC Architecture**     | Backend organization          |
| 🌐 **REST APIs**             | Client-server communication   |
| 🛰️ **External API Service** | Asteroid data integration     |
| ⚠️ **Risk Engine**           | Risk calculation and analysis |

---

# 🌌 3D Visualization

One of the core features of the platform is its interactive 3D environment.

The visualization layer uses **Three.js and WebGL** to create an immersive space environment.

### Visualization Components

```text
🌌 Interactive Space
       │
       ├── ☄️ Asteroids
       │
       ├── 🪐 Planets
       │
       ├── ⭐ Stars
       │
       ├── 🛰️ Orbital Paths
       │
       └── ✨ Particle Effects
```

### Main Components

| Component                  | Responsibility                    |
| -------------------------- | --------------------------------- |
| `Asteroid3DViewer.jsx`     | Individual asteroid visualization |
| `OrbitViewer3D.jsx`        | Orbital path visualization        |
| `CardOrbitViewer.jsx`      | Orbit visualization inside cards  |
| `Planet3D.jsx`             | 3D planet rendering               |
| `InteractiveStars3D.jsx`   | Interactive star field            |
| `FloatingParticles3D.jsx`  | Particle effects                  |
| `AsteroidBackground3D.jsx` | Animated space background         |

---

# ⚠️ Risk Assessment Engine

The backend includes a dedicated risk assessment service:

```text
backend/src/services/riskEngine.service.js
```

The engine processes asteroid information and applies multiple factors to generate a risk assessment.

Conceptually:

```text
Asteroid Data
     │
     ├── Size
     ├── Distance
     ├── Orbital Information
     ├── Velocity / Motion
     └── Historical Information
              │
              ▼
       Risk Calculation
              │
              ▼
        Risk Score
              │
              ▼
       Risk Assessment
```

> The risk engine is an application-level analytical model and should not be treated as an official astronomical hazard prediction system.

---

# 🛰️ Data Integration

The platform communicates with external asteroid data sources through the backend service layer.

```text
External API
     │
     ▼
externalApi.service.js
     │
     ▼
Data Validation
     │
     ▼
Data Processing
     │
     ▼
Risk Engine
     │
     ▼
REST API
     │
     ▼
React Dashboard
```

This architecture keeps external API logic separated from the frontend.

---

# 📊 Dashboard

The dashboard provides a centralized view of asteroid information and platform statistics.

### Dashboard capabilities

* ☄️ Asteroid information
* 📊 Statistical summaries
* ⚠️ Risk information
* 🌌 3D visualization
* 🛰️ Orbital visualization
* 🔍 Interactive asteroid cards

---

# 🔐 Authentication

The application includes a user authentication flow with:

```text
Signup
  ↓
Login
  ↓
Authentication
  ↓
Dashboard
```

Frontend authentication utilities are organized under:

```text
frontend/src/utils/auth.js
```

Authentication-related pages include:

```text
Login.jsx
Signup.jsx
```

---

# 📂 Project Structure

```text
asteroid-risk-assessment-platform/
│
├── 📁 backend/
│   │
│   ├── 📁 src/
│   │   ├── 📁 config/
│   │   ├── 📁 controllers/
│   │   ├── 📁 routes/
│   │   ├── 📁 services/
│   │   │   ├── externalApi.service.js
│   │   │   └── riskEngine.service.js
│   │   │
│   │   └── app.js
│   │
│   ├── server.js
│   └── package.json
│
├── 📁 frontend/
│   │
│   ├── 📁 src/
│   │   ├── 📁 components/
│   │   │   ├── Asteroid3DViewer.jsx
│   │   │   ├── AsteroidBackground3D.jsx
│   │   │   ├── AsteroidCard.jsx
│   │   │   ├── CardOrbitViewer.jsx
│   │   │   ├── FloatingParticles3D.jsx
│   │   │   ├── InteractiveStars3D.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── OrbitViewer3D.jsx
│   │   │   ├── Planet3D.jsx
│   │   │   └── StatsBar.jsx
│   │   │
│   │   ├── 📁 pages/
│   │   │   ├── Dashboard.jsx
│   │   │   ├── GetStarted.jsx
│   │   │   ├── Login.jsx
│   │   │   └── Signup.jsx
│   │   │
│   │   ├── 📁 services/
│   │   │   └── api.js
│   │   │
│   │   ├── 📁 utils/
│   │   │   └── auth.js
│   │   │
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── 📁 styles/
│   │
│   ├── vite.config.js
│   ├── eslint.config.js
│   ├── package.json
│   └── index.html
│
├── 📁 assets/
│   ├── dashboard.png
│   ├── 3d-visualization.png
│   └── demo.gif
│
├── .gitignore
└── README.md
```

---

# 🚀 Getting Started

## Prerequisites

Make sure the following are installed:

* **Node.js v14+**
* **npm** or **Yarn**
* Modern browser
* WebGL-compatible graphics support
* External API credentials if required

Check your versions:

```bash
node --version
npm --version
```

---

# ⚙️ Backend Setup

### 1. Navigate to backend

```bash
cd backend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create `.env`

Create:

```text
backend/.env
```

Example:

```env
PORT=5000
NODE_ENV=development
EXTERNAL_API_KEY=your_api_key_here
```

> Never commit `.env` or API credentials to GitHub.

---

# 🎨 Frontend Setup

Open a new terminal.

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Create:

```text
frontend/.env
```

Add:

```env
VITE_API_URL=http://localhost:5000/api
```

---

# ▶️ Running The Application

The project requires **two development servers**.

## Terminal 1 — Backend

```bash
cd backend
npm start
```

Backend:

```text
http://localhost:5000
```

---

## Terminal 2 — Frontend

```bash
cd frontend
npm run dev
```

Frontend:

```text
http://localhost:5173
```

Open the frontend URL in your browser.

---

# 📦 Production Build

## Frontend

```bash
cd frontend
npm run build
```

The production build will be generated in:

```text
frontend/dist/
```

## Backend

If a production build script is defined in `backend/package.json`:

```bash
cd backend
npm run build
```

> If the backend does not define a `build` script, use the production start command provided by its `package.json`.

---

# 🔌 API Documentation

### Base URL

```text
http://localhost:5000/api
```

### Available Endpoints

| Method | Endpoint           | Purpose                      |
| :----: | ------------------ | ---------------------------- |
|  `GET` | `/asteroids`       | Retrieve asteroid data       |
|  `GET` | `/asteroids/:id`   | Retrieve specific asteroid   |
| `POST` | `/risk-assessment` | Calculate risk assessment    |
|  `GET` | `/stats`           | Retrieve platform statistics |

> API behavior depends on the current backend implementation. Refer to the controller and route definitions for the authoritative endpoint contract.

---

# ⚡ Performance Considerations

The application incorporates several strategies to improve performance:

* Component-based React architecture
* Lazy loading where applicable
* Efficient React state management
* 3D rendering optimization
* API response caching
* Reusable visualization components
* Separation of frontend and backend responsibilities

---

# 🌐 Browser Compatibility

The application is designed for modern browsers with WebGL support.

| Browser | Support |
| ------- | :-----: |
| Chrome  |    ✅    |
| Firefox |    ✅    |
| Edge    |    ✅    |
| Safari  |    ✅    |

For the best 3D experience, use a recent version of a Chromium-based browser or another modern WebGL-capable browser.

---

# 🧪 Troubleshooting

## Frontend Issues

### 3D scene is not rendering

Check:

* WebGL support
* Browser console
* Graphics driver
* Three.js errors
* Browser hardware acceleration

---

### API requests are failing

Verify:

```text
VITE_API_URL
```

and make sure the backend is running:

```text
http://localhost:5000
```

---

## Backend Issues

Check:

```text
Node.js version
Environment variables
API credentials
Port availability
External API response
```

You can also check the backend terminal for server errors.

---

# 🔐 Security

Before pushing the project to GitHub, ensure that sensitive files are ignored.

Recommended `.gitignore`:

```gitignore
# Dependencies
node_modules/

# Environment files
.env
.env.*
!.env.example

# Build output
dist/
build/

# Logs
*.log
npm-debug.log*

# OS
.DS_Store
Thumbs.db
```

Never commit:

```text
API keys
Passwords
Tokens
Private credentials
.env files
```

---

# 🏆 Hackathon Project

<div align="center">

### 🚀 IIT Hackathon 2026

**Team Sniper**

</div>

The platform was developed as a collaborative hackathon project focused on combining **real-time data, intelligent risk analysis, full-stack development, and 3D visualization** into a single interactive experience.

---

# 👥 Team

### Team Sniper

| Member                   |
| ------------------------ |
| **Vivek Saha**           |
| **Tapan Kumar Panda**    |
| **Soumya Ranjan Sahoo**  |
| **Ranjan Kumar Mohanty** |

---

# 🗺️ Roadmap

Future development possibilities include:

* [ ] 📷 Enhanced asteroid imagery
* [ ] 🌌 More advanced orbital visualization
* [ ] 📈 Historical asteroid trend analysis
* [ ] 🔔 Risk notifications
* [ ] 🔍 Advanced asteroid search and filtering
* [ ] 📊 Advanced analytics dashboard
* [ ] 🧠 Improved risk modeling
* [ ] 🛰️ Additional astronomical data sources
* [ ] 📱 Mobile-responsive 3D optimization
* [ ] ☁️ Cloud deployment
* [ ] 🔄 Automated data refresh
* [ ] 🧪 Automated backend testing
* [ ] 📚 Complete API documentation
* [ ] 🚀 Production deployment

---

# 🤝 Contributing

Contributions are welcome.

### Development Workflow

```bash
# Create a feature branch
git checkout -b feature/AmazingFeature

# Make your changes

# Stage changes
git add .

# Commit
git commit -m "Add: AmazingFeature"

# Push branch
git push origin feature/AmazingFeature
```

Then open a Pull Request.

### Code Guidelines

* Follow the existing ESLint configuration
* Use meaningful variable and function names
* Keep components modular
* Separate business logic from UI logic
* Document complex algorithms
* Maintain consistent formatting
* Avoid committing secrets

---

# 📜 License

This project was developed as part of **IIT Hackathon 2026**.

If you intend to distribute the project publicly or allow external reuse, add an explicit open-source license such as the **MIT License**, subject to the project's team and event requirements.

---

# 👨‍💻 Project Team

<div align="center">

## Team Sniper 🚀

### Building Interactive Intelligence for Near-Earth Asteroid Analysis

<br>

**Vivek Saha • Tapan Kumar Panda • Soumya Ranjan Sahoo • Ranjan Kumar Mohanty**

<br>

<a href="https://github.com/soumyaranjan17">
<img src="https://img.shields.io/badge/GitHub-Soumyaranjan17-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br><br>

**React • Node.js • Express • Three.js • WebGL • REST APIs**

</div>

---

<div align="center">

### ☄️ Explore the Data. Visualize the Cosmos. Assess the Risk.

<br>

**Team Sniper — IIT Hackathon 2026**

⭐ If you find this project interesting, consider starring the repository.

</div>
