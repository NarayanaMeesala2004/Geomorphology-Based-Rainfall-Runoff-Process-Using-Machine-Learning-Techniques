# HydroFlow — ML Prediction Dashboard

A machine learning-based surface flow prediction system for hydrological catchment analysis.

---

## 📁 Project Structure

```
hydroflow-dashboard/
├── index.html              ← Main dashboard (single-file app)
├── README.md               ← Project documentation
├── assets/
│   ├── css/               ← (for future external stylesheets)
│   ├── js/                ← (for future external scripts)
│   └── images/            ← (for future images/icons)
└── .vscode/
    ├── settings.json       ← VS Code editor settings
    ├── extensions.json     ← Recommended extensions
    └── launch.json         ← Browser launch config
```

---

## 🚀 How to Run in VS Code

### Method 1: Live Server (Recommended)

1. Open VS Code
2. Go to **File → Open Folder** → select `hydroflow-dashboard/`
3. Install the **Live Server** extension (prompted automatically)
4. Right-click `index.html` → **"Open with Live Server"**
5. Browser opens at: `http://localhost:5500/index.html`

### Method 2: Direct Browser Open

1. Navigate to the project folder
2. Double-click `index.html`
3. It opens directly in your default browser

### Method 3: VS Code Terminal

```bash
# Open terminal in VS Code (Ctrl + `)
# Then run:
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

---

## 🧠 Features

| Feature | Description |
|---|---|
| 5 ML Models | XGBoost, Random Forest, Decision Tree, SVR, Linear Regression |
| 7 Parameters | Precipitation, Catchment Area, Slope, CN Number, Flow Length, Impervious %, Tension |
| Radar Chart | Visual comparison of input parameters |
| Model Comparison Table | R², RMSE metrics for all models |
| Feature Importance | Bar chart showing top influencing features |

---

## 🛠️ Tech Stack

- **HTML5** — Structure
- **CSS3** — Custom properties, Grid, Flexbox
- **Vanilla JavaScript** — Logic & DOM manipulation
- **Chart.js (CDN)** — Radar chart visualization
- **Google Fonts (CDN)** — Fraunces, DM Sans, DM Mono

> ⚠️ Requires internet connection for CDN fonts and Chart.js library.

---

## 📊 ML Models Included

| Model | Description |
|---|---|
| XGBoost | Gradient boosted trees — best overall |
| Random Forest | Ensemble of decision trees |
| Decision Tree | Single tree — interpretable |
| SVR | Support Vector Regression |
| Linear Regression | Baseline model |

---

## 👨‍💻 Author

HydroFlow ML Prediction Dashboard  
Built for surface runoff prediction using SB_1 Dataset
