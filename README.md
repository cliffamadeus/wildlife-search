# 🌍 iNaturalist Wildlife Search

A simple HTML/CSS/JavaScript web application that displays **iNaturalist observations** on an interactive map using the **Leaflet.js** mapping library. The app is designed to run locally using **npm live-server**.

---

## 📌 Features

* Fetches real-time observation data from the **iNaturalist API**
* Displays observations as markers on a **Leaflet interactive map**
* Lightweight frontend built with **HTML, CSS, and vanilla JavaScript**
* Runs locally with **live-server** for quick development

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6)**
* **Leaflet.js** – interactive maps
* **iNaturalist API** – biodiversity data
* **Node.js & npm**
* **live-server**

---

## 📂 Project Structure

```
.
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js** (includes npm)
* A modern web browser

---

### 🔧 Installation

1. Clone or download this repository:

   ```bash
   git clone https://github.com/cliffamadeus/wildlife-search.git
   cd wildlife-search
   ```

2. Install `live-server` (if not already installed):

   ```bash
   npm install -g live-server
   ```

---

### ▶️ Running the App

From the project root directory, run:

```bash
live-server
```

This will automatically open the application in your default browser and reload on file changes.

---

## 🗺️ APIs Used

### iNaturalist API

Used to fetch observation data such as species name, location, and date.

* API Docs: [https://api.inaturalist.org/v1/docs/](https://api.inaturalist.org/v1/docs/)

### Leaflet API

Used to render the interactive map and markers.

* Website: [https://leafletjs.com/](https://leafletjs.com/)

---

## 📸 Example Use Case

* Visualizing wildlife observations in a specific geographic area
* Learning how to integrate third-party APIs with maps
* Educational or demo projects related to biodiversity and GIS

---

## ⚠️ Notes

* No API key is required for basic iNaturalist API usage.
* Internet connection is required to load map tiles and API data.
* This project is intended for learning and demonstration purposes.

---

## 📄 License

This project is open-source and available under the **MIT License**.
