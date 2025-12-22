# Mary McHale - Interactive Professional Portfolio

## Overview
This repository contains the source code for my personal professional portfolio. As a Senior HR Business Partner with a background in Information Systems, I built this site to demonstrate the intersection of **People Strategy** and **Data Analytics**.

Unlike a static PDF resume, this project utilizes web technologies to visualize workforce data, regional scope, and operational impact.

## 🚀 Live Demo
[View the Live Site](https://marymchale1154.github.io/career-infographic)

## 🛠️ Technology Stack
This project is built as a lightweight, single-page application using modern front-end libraries via CDN (no build step required):

* **HTML5 & JavaScript (ES6+)**: Core structure and logic.
* **Tailwind CSS**: For responsive styling and a custom "GitHub Dark Mode" aesthetic.
* **Leaflet.js**: Used to create the interactive regional map, visualizing the North/South operational territories and headcount data.
* **Plotly.js**: Renders dynamic bar charts to visualize key impact metrics (Employees Supported, Hires Onboarded, Leaders Advised).
* **FontAwesome**: For UI iconography.

## ✨ Key Features
* **Interactive Regional Map**: A dynamic map utilizing OpenStreetMap tiles that allows users to explore the "Mid-Atlantic North" and "Mid-Atlantic South" operational territories. Hovering over regions displays specific headcount data and leadership structures.
* **Data Visualization**: A logarithmic bar chart visualizing high-volume metrics (8,000+ employees supported, 3,500+ hires).
* **Responsive Design**: Fully optimized for mobile and desktop viewing.
* **Animations**: Custom intersection observers create a "fade-in" effect as the user scrolls through the experience.

## 📂 Project Structure
```text
/
├── index.html        # Main entry point containing structure, styles, and scripts
├── README.md         # Project documentation
└── (assets/images)   # Profile images (hosted externally or locally)
