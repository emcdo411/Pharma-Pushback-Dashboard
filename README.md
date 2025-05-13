# 💊⚖️ PharmaPushbackDashboard

**A weaponized Shiny R dashboard exposing Big Pharma's billion-dollar resistance to U.S. drug price reform (1993–2025).**
This is **policy forensics**—fueled by reactive pipelines, PowerBI-inspired theming, and 🔥 high-impact geospatial visuals.

> 💼 \$373M lobbying | ⚖️ 8 lawsuits under Biden | 📺 \$150M ad campaigns
> 🎯 Built for researchers, journalists, and disruptors.

---

## 🧠 Table of Contents

* [🚀 Summary](#-summary)
* [🔍 Features](#-features)
* [🛠️ Tech Stack](#-tech-stack)
* [📦 Installation](#-installation)
* [🖥️ Usage](#-usage)
* [💻 Code](#-code)
* [🧭 Why This Matters](#-why-this-matters)
* [🔚 Conclusion](#-conclusion)
* [📜 License](#-license)

---

## 🚀 Summary

**PharmaPushbackDashboard** is a bleeding-edge, data-rich R/Shiny app analyzing pharmaceutical pushback against drug price reforms.
It slices across five presidencies (Clinton → Biden), blending 📊 **Plotly interactivity**, 🗺️ **Leaflet geospatial insights**, and 🎨 **thematic CSS weaponry**.

**Key payloads:**

* 💰 **\$373M** in lobbying (e.g., **CA-12** district: \$12.5M)
* ⚖️ **8 lawsuits** under Biden
* 📺 **\$150M** ad blitz in 2010 alone

This isn't your typical data viz—this is **investigative analytics**.

---

## 🔍 Features

### 🔥 Interactive Visuals

* 💵 Plotly charts: Lobbying, lawsuits, ad spend
* 📊 Lawsuit bars: Hover-scale 💥 +20% (`#8e44ad`)
* 🗺️ Leaflet map: District-wise lobbying bombs (e.g., CA-12 💣 \$12.5M)

### ⚙️ Reactive Controls

* 🕹️ Presidency filter: `Clinton → Biden`
* 📅 Year slider: `1990–2025`
* ⚡ dplyr-powered real-time data transformations

### 🎨 Theming Arsenal

* 🌑 Dark Mode: `#121212 → #1e272e`
* 🌕 Light Mode: `#6c757d → #495057`
* 🧬 Custom CSS gradients, Font Awesome icons, and 🔴 `#FF4136` loading spinners

### 🧯 Fail-Safe Engineering

* 🧰 `tryCatch` + `validate()` = resilient UX
* ⏳ `shinycssloaders`: Polished spinners with real-time vibes

### 🧭 Geospatial Intel

* 🗺️ CartoDB Leaflet tiles
* 📍 Markers scale to lobbying \$\$\$ by district

---

## 🛠️ Tech Stack

Built in **R 4.4.1** via **RStudio** — this dashboard flexes an elite lineup:

| ⚙️ Package        | 📌 Purpose                       |
| ----------------- | -------------------------------- |
| `shiny`           | Core app framework               |
| `plotly`          | Interactive graphs with hover FX |
| `leaflet`         | Dynamic geospatial mapping       |
| `dplyr`           | Lightning-fast data ops          |
| `shinycssloaders` | Slick loading UX                 |
| `htmlwidgets`     | JS-powered hover scaling         |

**Plus:**

* 🧬 **Custom CSS**: Gradient-rich PowerBI vibes
* ⚡ **JavaScript**: Hover logic via `htmlwidgets`
* 🌐 **Font Awesome**: CDN icons = extra UX punch

---

## 📦 Installation

### 🛑 Prereqs

* R ≥ 4.4.1
* RStudio
* Internet connection (Font Awesome + Leaflet tiles load remotely)

### 🔁 Clone This Repo

```bash
git clone https://github.com/YourUsername/PharmaPushbackDashboard.git
cd PharmaPushbackDashboard
```

### 📥 Install Dependencies

```r
install.packages(c(
  "shiny", "plotly", "leaflet", 
  "dplyr", "shinycssloaders", "htmlwidgets"
))
```

### 🧼 (Optional) Update

```r
update.packages()
```

---

## 🖥️ Usage

### 🏁 Launch the App

Open `app.R` in RStudio
Click ▶️ **Run App** or run:

```r
shiny::runApp()
```

🖱️ Open in browser → `http://127.0.0.1:XXXX`

---

### 💡 Dashboard Interactions

#### 🎛️ **Theme Toggle**

Switch between **Dark/Light Mode** via the theme selector 🌗

#### 🧩 **Summary Tab**

* Choose a presidency (e.g., *Trump*)
* Adjust year range (`1993–2025`)
* Watch lobbying (\$306M in 2020) + ad spend trends come alive

#### 🧭 **Congressional Tab**

* Explore **lawsuits** (e.g., *8 under Biden*, styled in `#8e44ad`)
* Dive into a **Leaflet map** with live lobbying hotspots (📍 CA-12: \$12.5M)

#### 📦 Info Boxes

* 📉 Drug Price Reduction (30%–80%)
* 🧠 Industry Stance
* 🗳️ Congressional Sentiment

---

## 🚀 Deploy (Optional)

🎯 Launch to shinyapps.io:

```r
library(rsconnect)
deployApp(appName = "PharmaPushbackDashboard")
```

---

## 🛠️ Troubleshooting

* ❌ **Font Awesome or Leaflet not loading?**
  → Requires internet. Offline? Remove `tags$link` and use `addTiles()`.

* ❓ **Check versions:**

  ```r
  sessionInfo()
  ```

---

## 💻 Code

**Full source code** lives in `app.R` and includes advanced CSS theming, reactivity logic, and error handling.
For deep CSS customizations, see `darkCSS` and `lightCSS` inside the script 🎨.

---

## 🧭 Why This Matters

This isn’t just a dashboard.
It’s a 🔬 **lens into 30+ years of pharmaceutical influence**, wrapped in open-source armor.

📢 Whether you're a:

* 🎓 Researcher
* 📰 Investigative journalist
* 🏛️ Policy strategist
* 💊 Healthcare reform advocate

…**PharmaPushbackDashboard** gives you the data **they** don’t want front and center.

---

## 🔚 Conclusion

**Big Pharma pays big money to hide this story.**
We built a tool to show it loud, clear, and interactive.

⚔️ Let the data speak.

---

## 📜 License

[MIT License](LICENSE)

---

Let me know if you want me to generate a banner image or GitHub badges to top it off.
