# Interactive Timeline & Map of Personalities

An interactive Dash application that visualizes historical and contemporary figures on both a timeline and a duotone map. The project includes a richly populated dataset featuring key Islamic figures (including the Prophet, the 12 Imams, caliphs, scholars, Sufi saints, and Shia scholars) as well as major non‑Muslim historical figures, rulers, military leaders, Renaissance personalities, scientists, and modern figures.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Download Feature](#download-feature)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This project provides an interactive visualization tool that allows users to explore a timeline and map of important personalities spanning from late antiquity to modern times. Built with Python, Dash, and Plotly, the application offers:
- A **timeline view** where each figure is represented as a colored rectangle spanning from their birth year to their death year (with a placeholder year for those still living).
- A **duotone map view** that plots markers for the birth locations of these figures on a clean "carto-positron" background.
- Dynamic filtering options by category, era, and name search.
- Toggle options for light and dark themes as well as multiple color schemes.
- A download feature to export the current view as an HTML file.

## Features

- **Interactive Timeline:**  
  Visualizes each personality with a horizontal bar representing their lifespan. Hovering over each bar shows detailed information.

- **Duotone Map View:**  
  Displays markers for the birth locations on a duotone "carto-positron" map style. The map automatically centers based on the data.

- **Filtering Options:**  
  - Filter by Category (e.g., Prophet, Imam, Sufi Saint, Shia Scholar, Non‑Islamic Ruler, etc.).
  - Filter by Era (e.g., Early Islamic Period, Renaissance, Modern Era, etc.).
  - Search by Name.

- **Theme and Color Schemes:**  
  Choose between Light and Dark modes, and select from three different color schemes (Default, Pastel, Vibrant).

- **Download Feature:**  
  Export the current view (timeline or map) as a standalone HTML file.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/interactive-timeline-map.git
   cd interactive-timeline-map
# ProjectTimeline
