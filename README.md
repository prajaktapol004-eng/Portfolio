# Prajakta Pol — Professional Engineering Portfolio

> **Aspiring PLC & Industrial Automation Engineer**  
> *Targeting Entry-Level PLC Automation, Control Systems, and Electronics/Service Engineer roles in Pune, Maharashtra, India.*

---

## 🌟 Overview & Recruiter Focus

This website is a modern, responsive personal portfolio built for **Prajakta Pol**, an Electronics & Telecommunication Engineering graduate (**8.25/10 CGPA**) with a **Post Graduate Diploma in Industrial Automation (PGDIA)** and hands-on internship exposure at **DRDO** and **Laxmi Controls**.

The website features:
- **Modern Industrial-Tech Aesthetic**: Inspired by Siemens and Rockwell Automation control interfaces, featuring dark navy/charcoal styling (`#0B1120`, `#0F172A`) with electric blue (`#38BDF8`) and industrial cyan (`#06B6D4`) accents.
- **Interactive PLC Ladder Logic Simulator**: Live browser-based simulator enabling recruiters to test DOL Motor Starter latching logic (I0.0 Start, I0.1 Stop, I0.2 Overload trip, Q0.0 Contactor coil), Timer On-Delay (TON) cycles, and Proximity Sensor part counter (CTU).
- **Recruiter Credibility Standards**: Clearly distinguishes academic training exercises and simulations from workplace deployments. Accurately portrays internship exposure without exaggerated claims.
- **Zero Build Friction**: Modular component architecture with centralized data configuration in `assets/js/data.js`. No compilation steps needed; edits take effect immediately upon browser refresh.

---

## 📁 Project Directory Structure

```text
prajakta-portfolio/
│
├── index.html                   # Main semantic, accessible, SEO-optimized entry point
├── favicon.svg                  # Custom high-tech industrial favicon ("PP")
├── README.md                    # Project documentation & hosting guide
├── preview-server.js            # Built-in local preview server
├── generate-pdf.js              # Node.js PDF generator for resume updates
│
├── assets/
│   ├── css/
│   │   └── styles.css           # Industrial dark theme, glassmorphic cards, print styles
│   │
│   ├── js/
│   │   ├── data.js              # Central data file (profile, skills, projects, awards)
│   │   ├── app.js               # Component renderer, modal manager, smooth scroll
│   │   └── ladder-sim.js        # Interactive IEC 61131-3 PLC ladder logic simulator
│   │
│   └── images/
│       ├── favicon.svg                  # Favicon asset
│       ├── profile-placeholder.svg      # Professional engineering badge placeholder
│       ├── project-water-quality.svg    # ESP32 multi-sensor telemetry schematic
│       ├── project-energy-meter.svg     # ZMPT101B voltage transformer & Telegram bot
│       ├── project-walkie-talkie.svg    # ESP-NOW encrypted voice transceiver
│       ├── project-silk-fibroin.svg     # Biomaterial membrane filtration diagram
│       ├── internship-drdo.svg          # DRDO Cobalt-60 & gamma spectrometry setup
│       ├── internship-laxmi.svg         # Industrial panel & DIN rail switchgear layout
│       ├── plc-ladder-motor.svg         # DOL Motor starter ladder logic diagram
│       ├── plc-ladder-timer.svg         # Timer On-Delay (TON) ladder diagram
│       ├── plc-ladder-sensor.svg        # Part counter & diverter ladder diagram
│       └── industrial-mesh.svg          # Technical background grid & bus traces
│
└── resume/
    └── Prajakta_Pol_Resume.pdf  # Genuine downloadable, print-ready PDF resume
```

---

## 🚀 How to Run and View the Portfolio Locally

### Method 1: Instant Browser View (No tools required)
Simply double-click `index.html` or drag it into any web browser (Chrome, Edge, Firefox, Brave). Everything is self-contained and renders immediately.

### Method 2: Using the Built-In Local Preview Server
Open a terminal in the project directory and run:
```bash
agy-node preview-server.js
```
Then open your browser at:
```
http://127.0.0.1:3000
```

---

## ✏️ How to Customize Your Details in 2 Minutes

All portfolio content is neatly organized in **[`assets/js/data.js`](assets/js/data.js)**. You do not need to rewrite HTML or recompile anything:

1. **Update Profile Photo**:
   - Save your photo as `assets/images/prajakta-photo.jpg`.
   - Open `assets/js/data.js` and change `profilePhoto: "assets/images/prajakta-photo.jpg"`.
2. **Update Social / Professional Links**:
   - In `assets/js/data.js`, replace `linkedinPlaceholderUrl` and `githubPlaceholderUrl` with your actual profile links.
3. **Update Resume File**:
   - Whenever you export a new resume PDF, save it directly to `resume/Prajakta_Pol_Resume.pdf`. The download button and fullscreen preview modal will immediately use your latest version.
4. **Add New Projects or Experience**:
   - Add new entries to `featuredProjects`, `automationPractice`, or `internships` in `assets/js/data.js`.

---

## 🌐 Free 1-Click Hosting Guide

### Deploying to GitHub Pages (Recommended)
1. Create a free GitHub repository named `prajakta-portfolio`.
2. Push all files to the `main` branch.
3. In GitHub, go to **Settings** > **Pages** > Select `main` branch and `/ (root)` folder > Click **Save**.
4. Your website will be live at `https://<your-username>.github.io/prajakta-portfolio/`!

### Deploying to Netlify / Vercel
- Simply drag and drop the `prajakta-portfolio` folder into the [Netlify Drop](https://app.netlify.com/drop) dashboard. It will deploy within 5 seconds with a custom URL and free SSL.

---

## 📞 Contact Information
- **Candidate**: Prajakta Pol
- **Specialization**: Electronics & Telecommunication (B.Tech 8.25 CGPA) | PGDIA Industrial Automation
- **Target Role**: Entry-Level PLC / Industrial Automation Engineer
- **Preferred Location**: Pune / Solapur, Maharashtra, India
- **Direct Email**: [polprajakta07@gmail.com](mailto:polprajakta07@gmail.com)
