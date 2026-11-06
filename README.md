# Pelayo Pache Rodríguez – Personal Engineering Portfolio 🚀

Engineering Portfolio website showcasing hardware design, embedded systems firmware, aerospace testbeds, and systems engineering projects.

Designed as an upgraded, responsive, and minimalist portfolio based on the two-column format, featuring deep integration with GitHub repositories, technical competency pills, detailed project breakdowns, and direct resume download.

---

## 📁 Project Structure

```text
portfolio pelayo/
├── index.html                     # Main semantic HTML5 portfolio layout
├── style.css                      # Modern responsive styling & CSS design system
├── profile.png                    # High-resolution profile portrait
├── PelayoPacheRodriguez_CV.pdf    # Direct downloadable PDF resume
└── README.md                      # Documentation & GitHub deployment guide
```

---

## 🌟 Key Highlights & Enhancements

1. **Two-Column Architecture**:
   - **Left Column**: Fast-access Contact with direct LinkedIn & GitHub links, categorized Technical Stack (EDA/Hardware, Embedded & Firmware, Systems & Simulation, Software), Experience timeline, Honors/Certifications, Education, and Languages.
   - **Right Column**: Profile hero card with status badge, Research & Fellowship (Ministry of Education & Spacecraft Attitude Control microgravity bench), and detailed Featured Projects.
2. **Deep Project & Git Integration**:
   - [Spacecraft Attitude Control System (SACS) & Testbed](https://github.com/pprguez2005-byte/spacecraft-attitude-control-system) (TFG & Research Grant, Input Shaping ZV/ZVD, parametric CAD via Python).
   - [Uniovi eTech-Racing (Formula Student Electric)](https://linkedin.com/in/pelayo-pache-rodriguez) (Multi-layer PCB in Altium Designer, CAN Bus 500 kbps, VHDL Vivado).
   - [Smart Home Domotics ESP32-C3 SuperMini](https://github.com/pprguez2005-byte/Domotica-ESP32-C3) (RISC-V 32-bit embedded web server, WebSockets, OpenSpec).
   - [Electric Vehicle Architecture in SysML v2](https://github.com/pprguez2005-byte/Coche-sysml-) (MBSE, state machines, powertrain & battery modes).
   - [ART – Asturias Rural Tech Booking Platform](https://github.com/pprguez2005-byte/El-rincon-del-asador) (Top 12 Innovation Finalist in Uniovi Emprende).
   - [Uniovi Robotics Workshop GenAI](https://github.com/pprguez2005-byte/uniovi-robotics-workshop-genai) (Python, Angular, MATLAB Engine API).
3. **LinkedIn & Socials Access**:
   - LinkedIn: [linkedin.com/in/pelayo-pache-rodriguez](https://linkedin.com/in/pelayo-pache-rodriguez)
   - GitHub: [github.com/pprguez2005-byte](https://github.com/pprguez2005-byte)
   - Email: [pprguez2005@gmail.com](mailto:pprguez2005@gmail.com)

---

## 💻 How to View & Test Locally

Simply double-click `index.html` to open it in any browser (Google Chrome, Edge, Firefox, Brave, Safari).

Alternatively, run a local web server:
```bash
# Using Python
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

---

## 🚀 How to Publish to GitHub Pages

You can publish this portfolio to GitHub in less than 2 minutes:

### Option A: Create a Dedicated Portfolio Repository (e.g. `pprguez2005-byte.github.io`)
This creates your main personal website URL at `https://pprguez2005-byte.github.io`:

1. Create a new repository on GitHub named:
   **`pprguez2005-byte.github.io`** (make it Public).
2. In your terminal, open this directory:
   ```bash
   cd "C:\Users\Usuario\Desktop\Masters\Documentos entregar\CV\DEFINITIVO\portfolio pelayo"
   ```
3. Initialize git, commit, and push:
   ```bash
   git init
   git add .
   git commit -m "feat: initial release of Pelayo Pache engineering portfolio"
   git branch -M main
   git remote add origin https://github.com/pprguez2005-byte/pprguez2005-byte.github.io.git
   git push -u origin main
   ```
4. Done! Your website will be live at:
   **`https://pprguez2005-byte.github.io`**

### Option B: Deploy inside a `portfolio` repository
1. Create a repository on GitHub named `portfolio` (Public).
2. Push the files to that repository:
   ```bash
   git init
   git add .
   git commit -m "feat: engineering portfolio website"
   git branch -M main
   git remote add origin https://github.com/pprguez2005-byte/portfolio.git
   git push -u origin main
   ```
3. In GitHub, go to **Settings > Pages** -> select Branch **`main`** / Folder **`/(root)`** -> Click **Save**.
4. Your website will be available at:
   `https://pprguez2005-byte.github.io/portfolio/`
