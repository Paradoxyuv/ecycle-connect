# ♻️ E-Cycle Connect

**Give old electronics another loop.**

E-Cycle Connect is a web prototype that helps people decide whether an old device should be **repaired, reused or recycled**, shows where to take it, and tracks it until its journey is complete.

> Team **LOGICLOOP** · Technology and Sustainability (2026CSAE102) · Milestone 2

---

## 🌍 Why this project

Old phones, chargers and laptops often end up in drawers, dustbins or informal scrap channels because people do not know what can be saved or where to take it safely. E-Cycle Connect answers both questions in under a minute.

| SDG | Link to the project |
|---|---|
| **SDG 12** Responsible Consumption and Production (main) | Promotes repair, reuse and responsible recycling |
| SDG 9 Industry, Innovation and Infrastructure | Digital tracking for a circular e-waste system |
| SDG 11 Sustainable Cities and Communities | Safer e-waste handling in communities |
| SDG 13 Climate Action | Less unnecessary production and disposal |

## ✨ What the prototype does

| Step | What happens |
|---|---|
| **1. Register** | Choose the device type, enter the model, set its age and condition |
| **2. Recommend** | A rule engine suggests reuse, repair or recycle, with a one-line reason |
| **3. Match** | Nearby partners are listed, verified ones first |
| **4. Protect** | Unverified partners are blocked for recycling, so waste is not pushed somewhere less safe |
| **5. Track** | Book a drop-off and follow the device through its stages |
| **6. Impact** | See devices handled and the estimated e-waste kept out of landfill |

### Recommendation rules

| Input | Outcome |
|---|---|
| Device type is Battery | Recycle (hazardous) |
| Works fine | Reuse |
| Minor fault | Repair |
| Not working | Recycle |

## 🚀 How to run

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

No install, build step or internet connection is needed. The page uses Google Fonts when online and falls back to system fonts when offline.

## 🧱 How it is built

- Single-page app in plain **HTML, CSS and JavaScript** (one file, no libraries)
- Data is stored in the browser with **localStorage**
- Dark mode and reduced-motion settings are respected
- Layers: presentation (Register, Track, Impact views), application logic (rule engine, partner matching, journey tracker, impact totals) and data (device records, partner directory, stage definitions)

## 📁 Files

| File | Purpose |
|---|---|
| `index.html` | The working prototype |
| `README.md` | This page |

## ⚠️ Limits of the prototype

- Collection points, distances and device weights are **sample data**, not real businesses.
- Weights are rough estimates used only to illustrate impact.
- Partners do not update stages themselves yet. The "Advance stage" button simulates progress.
- Devices are entered manually. Scanning is planned but not built.

## 🛣️ Planned next

- Real partners with a verification process
- Backend and shared database so partners can update stages
- Live map distances
- Testing with students and a repair or recycling partner

## 👥 Team

| Name | ID |
|---|---|
| Ankur Sharma | S26CSEU2729 |
| Yuvraj Dua | S26CSEU2766 |
| Nishant Sharma | S26CSEU2512 |
| Harsh Tyagi | S26CSEU2739 |
| Aryan Sinha | S26CSEU2537 |
