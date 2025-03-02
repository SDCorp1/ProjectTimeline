Below is a detailed README file in Markdown format that you can use for your GitHub repository:

```markdown
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
   ```

2. **Install the Required Packages:**

   Make sure you have Python installed. Then, install the dependencies using pip:

   ```bash
   pip install dash plotly pandas
   ```

## Usage

1. **Run the Application:**

   Execute the app using Python:

   ```bash
   python app.py
   ```

2. **Open in Browser:**

   Once the server is running, open your web browser and navigate to [http://127.0.0.1:8050](http://127.0.0.1:8050) to interact with the application.

3. **Interacting with the App:**

   - Use the dropdown menus to filter by **Category** and **Era**.
   - Use the search box to filter by **Name**.
   - Toggle between **Timeline** and **Map** views.
   - Choose your preferred **Theme** and **Color Scheme**.
   - Click the **Download Current View** button to export the current visualization as an HTML file.

## Dataset

The dataset is embedded directly within the code and includes:

- **Islamic Figures:** Prophet Muhammad, the four Rashidun Caliphs, the 12 Imams, Umayyad and Abbasid rulers, classical jurists and scholars, and key Sufi and Shia scholars.
- **Non‑Muslim Figures:** Major non‑Muslim rulers (e.g., Heraclius, Charlemagne, Napoleon Bonaparte), Renaissance figures (e.g., Leonardo da Vinci, Michelangelo, Martin Luther, Christopher Columbus, Queen Elizabeth I), scientists (e.g., Isaac Newton, Albert Einstein, Stephen Hawking), and modern figures (e.g., Barack Obama, Bill Gates, Marie Curie).

The dataset uses approximate coordinates for mapping purposes. You can extend or refine the dataset by editing the `data` list in the code.

## Download Feature

The application includes a download button that exports the current view (timeline or map) as an HTML file. This is achieved using Dash’s `dcc.Download` component combined with Plotly's `to_html` method.

## Contributing

Contributions are welcome! If you have additional data or improvements to suggest:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Open a pull request with a description of your changes.

Please follow the repository’s coding style and add tests if applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, please feel free to reach out via GitHub Issues or contact danialahmed.92@gmail.com.

---

*Happy Coding!*
```

You can copy and paste this README.md file into your repository’s root. Adjust the details (like repository URL, email, and dataset if needed) to suit your project.
