# Moncy Portfolio Website

## 1. Project Overview
This project is a dynamic, interactive 3D portfolio website. It features a fully responsive design, custom GSAP animations, and integrated Three.js/React Three Fiber 3D models to create a rich and engaging user experience.

**Tech Stack:**
- **Framework**: React.js / Vite
- **TypeScript**: Used for robust type safety
- **3D Graphics**: Three.js, `@react-three/fiber`, `@react-three/drei`
- **Animations**: GSAP (GreenSock), `gsap-trial` (SplitText, ScrollSmoother)
- **Physics**: `@react-three/rapier`, `@react-three/cannon`

---

## 2. Prerequisites
Ensure you have the following installed before setting up the project:
- **Node.js**: `v18.0.0` or higher (Recommended: Latest LTS version)
- **NPM**: `v9.0.0` or higher (Comes bundled with Node.js)
- **Git** (optional, but recommended for version control)

---

## 3. Installation Steps (Step-by-Step)
To get this project running on your local machine, follow these instructions:

1. **Clone the repository** (if not already done):
   ```bash
   git clone <repository_url>
   cd Portfolio-Website-main
   ```

2. **Clean up old environments** (Recommended for first-time setup or recovery):
   If you have old installed modules, forcefully remove them:
   ```bash
   # Windows (PowerShell)
   Remove-Item -Recurse -Force node_modules -ErrorAction SilentlyContinue
   Remove-Item -Force package-lock.json -ErrorAction SilentlyContinue
   npm cache clean --force

   # Mac/Linux
   rm -rf node_modules package-lock.json
   npm cache clean --force
   ```

3. **Install Dependencies**:
   Install all node packages using npm:
   ```bash
   npm install
   ```
   *(Note: You may safely ignore `three-mesh-bvh` deprecation warnings).*

4. **Environment Setup**:
   This project does not strictly require an `.env` file for local development. However, if any external API integrations are added later, place them in an `.env.local` file at the root directory following standard Vite conventions (`VITE_API_KEY=...`).

---

## 🛠️ Instructions

I have modified the GSAP Club plugins using trial versions.  
⚠️ Note: Trial plugins cannot be used for production or hosting.

For official GSAP Club plugins, refer here:  
https://gsap.com/docs/v3/Installation/

---

## ⚙️ Tech Stack

React • TypeScript • GSAP • Three.js • WebGL • HTML • CSS • JavaScript

---

## 🎨 Assets Usage

Some 3D assets included in this repository are free to use for learning purposes.

However:

- The original 3D avatar used on my live portfolio is NOT included in this repository
- That avatar is a custom asset created over ~1 month
- It is not open source and not available for reuse

Any usage, extraction, or redistribution of that avatar from my live website is strictly prohibited.

---

![Protfolio-Preview](https://github.com/user-attachments/assets/3c4557e7-6392-4928-b8a9-7b2476ef4edd)

---

## 7. Future Reusability
This repository has been fully sanitized and structurally fixed for maximum reproducibility. 
Any new developer onboarding to this project simply needs to:
1. Guarantee Node.js version >= 18 is active.
2. Run standard installation protocols (`npm i`).
3. Trust the provided TS Typings (`vite-env.d.ts`). 
4. The configurations (`package.json`, `tsconfig.json`, `vite.config.ts`) are pre-calibrated to run seamlessly out of the box on Windows/Mac/Linux.
