# Urban Planning and Design – Visualization Dashboard

## Features
- Visualizes urban metrics like **population density**, **green space availability**, **traffic**, and **pollution**.
- Uses interactive **3D hologram-style scatter plots** for immersive data analysis.
- Helps compare multiple neighborhoods on key urban planning indicators.
- Supports data-driven insights for sustainable city development.

## Technology Used
- **Languages:** Python  
- **Libraries & Tools:**  
  - `pandas` – for data manipulation  
  - `numpy` – for numerical operations  
  - `plotly` – for creating 3D interactive visualizations  

## How It Works
- The tool reads neighborhood-level urban data including population, area, green space, traffic, and pollution indices.
- Calculates key urban planning metrics:
  - **Population Density** = Population / Area
  - **Green Space Ratio** = Green Space / Area
  - **Green Space per Person** = Green Space / Population
  - **Traffic-Green Ratio** = Traffic Index / (Green Space + 0.01)
- Displays the results using **three 3D plots**:
  1. **Population Density** – visualized using a 3D scatter plot.
  2. **Green Space Ratio** – displayed with green-tinted markers.
  3. **Traffic vs Pollution Index** – overlaid lines for comparative view.

## Data Collection
- The data is simulated for demo purposes.
- In real applications, such data may be sourced from:
  - Government open data portals (e.g., census, smart cities datasets)
  - Pollution and traffic monitoring systems
  - GIS and satellite imagery

---

*Developed as part of the Urban Planning & Design Project*
