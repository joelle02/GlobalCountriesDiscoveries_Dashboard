# Global Countries Discoveries Visualization

This project is a data visualization dashboard that provides insights into various socio-geographic and economic aspects of countries around the world. It uses **Vega-Lite** visualizations embedded in an HTML page to present interactive charts and graphs.

## Features

- **Population Density Visualization**: A choropleth map displaying population density per square mile for countries worldwide.
- **Economic Sector Distribution**: A bar chart comparing the contributions of service, agriculture, and industry sectors to GDP in selected regions.
- **Net Migration Analysis**: A visualization of net migration values across different world regions.
- **Literacy Rate vs. Phone Usage**: A scatter plot exploring the relationship between literacy rates and phone usage in various countries.
- **Climate and Crop Composition**: A chart analyzing the relationship between climate types and crop production in different countries.

## Technologies Used

- **HTML/CSS**: For structuring and styling the webpage.
- **Vega-Lite**: For creating interactive and visually appealing data visualizations.
- **JavaScript**: For embedding Vega-Lite visualizations and handling interactivity.
- **VS Code Live Server**: For local development and testing.

## How to Run the Project

1. Clone the repository or download the project files.
2. Ensure the following files are in the same directory as `index.html`:
   - `map.vg.json`
   - `economic.vg.json`
   - `net_migration.vg.json`
   - `phone_literacy.vg.json`
   - `crop_climate.vg.json`
3. Use a local server to serve the project:
   - **Option 1**: Use VS Code Live Server:
     - Open the project folder in VS Code.
     - Right-click on `index.html` and select **"Open with Live Server"**. (ensure Chrome is set as your default browser, copy and paste the link from your specified browser on Chrome if otherwise).
   - **Option 2**: Use Python's HTTP server:
     ```bash
     python -m http.server 8000
     ```
     Then, open `http://localhost:8000/index.html` in your browser.
4. Interact with the visualizations in your browser.

## Project Highlights

- **Interactive Visualizations**: Hover over charts for additional insights and use dropdowns (if applicable) to filter data by region.
- **Data Storytelling**: Each visualization is accompanied by a brief description to help users understand the insights.
- **Responsive Design**: The layout adapts to different screen sizes for better usability.

## Author

This project was created by **Joelle Tay Rui Ning** as part of an academic assignment. It demonstrates skills in data visualization, web development, and storytelling through data.

## Contact

For any inquiries, feel free to reach out via LinkedIn or email at joelletay@hotmail.com.

---

Thank you for reviewing this project!
