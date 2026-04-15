# Hi, I'm Derek Ike 👋

### Logistics · Spatial Data · Software

_Architecture & logistics professional turned developer —_  
_building tools at the intersection of infrastructure, GIS, and data._

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Derek%20Ike-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/derekike)  
[mailto:derek\_ike@outlook.com](mailto:derek_ike@outlook.com)  
[![Location](https://img.shields.io/badge/%F0%9F%93%8D-Toronto%2C%20ON%20Canada-1f2937?style=flat-square)](#)  
[![Status](https://img.shields.io/badge/Open%20to-IT%20Roles%20%26%20Collaboration-10B981?style=flat-square)](#)

---

## 🧠 About Me

```python
derek = {
    "name"       : "Derek Ike (Chukwuemeka Ike)",
    "location"   : "Toronto, ON, Canada",
    "education"  : "MSc Spatial Planning & Sustainability — Umeå University (2026)",
    "background" : ["Architecture", "Last-Mile Logistics", "Site Supervision", "GIS"],
    "experience" : ["Instabox Sweden (logistics ops)", "CAD drafting", "Prairie Nordic (founder)"],
    "languages"  : ["English (fluent)", "Swedish (basic)"],
    "building"   : "Prairie Nordic Integrated Services — rural Alberta logistics infrastructure",
    "seeking"    : ["IT roles", "Data / GIS positions", "Logistics tech"],
}

```

I have **5+ years** across architecture, construction, and logistics operations in Canada and Europe.  
Now applying that domain knowledge through code — building data pipelines, web apps, and GIS tools  
that solve real infrastructure problems.

---

## 🛠️ Tech Stack

### Languages & Data

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Libraries & Tools

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)  
![Leaflet.js](https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white)

### Spatial & Design

![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white)  
![GeoJSON](https://img.shields.io/badge/GeoJSON-FF6B35?style=for-the-badge&logo=mapbox&logoColor=white)  
![AutoCAD](https://img.shields.io/badge/AutoCAD-E51050?style=for-the-badge&logo=autodesk&logoColor=white)

### Platforms & Deployment

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)  
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)  
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

---

## 📌 Featured Projects

### 🚛 [logistics-data-pipeline](https://github.com/derekike/logistics-data-pipeline)

> **Python · Pandas · NumPy · Matplotlib**

A full data pipeline that cleans, processes, and analyses last-mile delivery route  
data across 16 rural Alberta municipalities.

| What it does | Output |
| --- | --- |
| Loads 500-record CSV with realistic noise | Validated clean dataset |
| Audits & fixes missing values, bad types, negatives | `output/cleaned_routes.csv` |
| 6 analysis modules: zones, hubs, vehicles, time patterns, efficiency, success rates | `output/summary_report.csv` |
| Generates 10 publication-quality charts | `output/charts/` |

```bash
git clone https://github.com/derekike/logistics-data-pipeline
pip install -r requirements.txt
python main.py

```

**Key finding:** Camrose and Two Hills flagged as underserved — high avg distance (31+ km),  
low success rate (32–43%), strong case for new hub placement.

---

### 🌐 [logistics-web-app](https://github.com/derekike/logistics-web-app) · [Live Demo →](https://prairie-nordic.netlify.app)

> **HTML · CSS · JavaScript · Deployed on Netlify**

A clean, responsive single-page web application presenting Prairie Nordic's services,  
coverage zones, and live data dashboard — built with zero dependencies.

**Features:**

-   🏠 Hero section with animated stat counters
-   🔎 Zone cards with interactive hub filter
-   📊 Data dashboard pulling directly from the pipeline analysis
-   📬 Client-side validated inquiry form
-   📱 Fully mobile-responsive

```
No build step. No npm. Open index.html — it just works.

```

---

### 🗺️ [gis-logistics-visualizer](https://github.com/derekike/gis-logistics-visualizer) · [Open Map →](https://prairie-nordic-gis.netlify.app)

> **Leaflet.js · GeoJSON · Vanilla JS**

An interactive GIS web map visualising distribution hubs, delivery zones, and route  
corridors across rural Alberta — **this is the killer project.**

**Map features:**

-   📍 **4 hub markers** at real GPS coordinates (Leaflet custom SVG icons)
-   ⭕ **16 zone circles** sized proportionally to delivery volume
-   🛣️ **14 route corridors** as colour-coded dashed polylines per hub
-   🔘 **Layer toggles** — Hubs / Zones / Routes / 30 km Radius
-   🔍 **Hub filter** — isolates one hub's zones and flies the map to it
-   📋 **Rich popups** with full delivery metrics per feature
-   📊 **Live sidebar stats** that update on filter
-   📱 **Mobile-first** — sidebar collapses to burger on small screens

**Spatial data covers:**  
Leduc County · Athabasca · Vegreville · Ponoka · Red Deer County ·  
Lacombe · Wetaskiwin · Stettler · Camrose · Two Hills · Bonnyville ·  
Lloydminster · Wainwright · Vermilion · Provost · Cold Lake

---

## 📊 GitHub Stats

![Derek's GitHub Stats](https://github-readme-stats.vercel.app/api?username=derekike&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=2563EB&icon_color=10B981&text_color=e2e8f0)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=derekike&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=2563EB&text_color=e2e8f0)

---

## 🌍 Background That Shapes My Work

```
📐  BSc Architecture          → Systems thinking, spatial analysis, technical drawing
🏗️  Site Supervision          → On-the-ground logistics, scheduling, quality control
📦  Instabox Sweden           → European last-mile delivery ops, route efficiency
🎓  MSc Spatial Planning      → GIS methodology, sustainability, land-use frameworks
🏢  Prairie Nordic (Founder)  → Applying all of the above to a real infrastructure problem

```

I don't build toy projects.  
Every repo here connects directly to a real business problem I understand from ground level.

---

## 🤝 Let's Connect

I'm actively looking for **IT support**, **data analyst**, **GIS technician**, or  
**logistics tech** roles in Toronto or remote across Canada.

If you're building something in:

-   🚚 Logistics / supply chain technology
-   🗺️ GIS / geospatial data
-   📊 Data pipelines / analytics
-   🏙️ Urban / rural infrastructure

**I want to hear from you.**

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/derekike)  
[![Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ike.emeka@gmail.com)  
[![Prairie Nordic](https://img.shields.io/badge/Prairie%20Nordic%20Web%20App-10B981?style=for-the-badge&logo=leaflet&logoColor=white)](https://prairie-nordic.netlify.app)

---

_"Rural Alberta lacks the last-mile logistics infrastructure that urban centres take for granted._  
_I'm building the data and technology layer that makes it viable."_

— Derek Ike, Founder — Prairie Nordic Integrated Services Ltd.