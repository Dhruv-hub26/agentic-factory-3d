# 🏭 Agentic Factory: Interactive 3D Workshop

An interactive, high-fidelity 3D digital-twin simulation of an automated assembly line pipeline built for agentic workflows. Featuring dynamic multi-angle camera views, cutaway structural breakdowns, and live station inspection.

🚀 **Live Demo:** [https://agentic-factory-3d-ebon.vercel.app/](https://agentic-factory-3d-ebon.vercel.app/)

---

## ✨ Features

- **Interactive 3D Assembly Simulation:** Full 360° orbit, pan, and zoom controls around the central conveyor assembly rig.
- **Cinematic Camera Presets:** Instant camera transitions to Overview, Side, Top, Station, and Flight perspectives.
- **Inspection Modes:**
  - **Assembled:** Complete functional pipeline view.
  - **Cutaway:** Structural internal mechanics exposure.
  - **Stations:** Focused breakdown on distinct operations (Storefront, Processing, Output).
- **Industrial Cyber Aesthetic:** Dark-mode UI with high-contrast amber/orange telemetry indicators and responsive overlays.
- **Performance Optimized:** Seamless frame rates powered by WebGL/Three.js integrated into React.

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router), React 19 / 18, TypeScript
- **3D Graphics & Engine:** Three.js / React Three Fiber / Drei
- **Styling:** Tailwind CSS, PostCSS
- **Deployment:** Vercel

---

## 🚀 Getting Started

Follow these steps to run the project locally on your machine:

### 1. Clone the repository
```bash
git clone [https://github.com/Dhruv-hub26/agentic-factory-3d.git](https://github.com/Dhruv-hub26/agentic-factory-3d.git)
cd agentic-factory-3d
2. Install dependencies
Bash
npm install
3. Run development server
Bash
npm run dev
Open http://localhost:3000 in your browser to inspect the application.

📦 Project Structure
Plaintext
├── app/                  # Next.js App Router (Layout & Core Page)
├── components/           # UI components, 3D Canvas, Overlays, and Controls
├── lib/                  # Helper utilities and animation lerp formulas
├── public/               # 3D assets, textures, and static media
└── styles/               # Global styling and Tailwind directives
👤 Author
Dhruv Mehra 