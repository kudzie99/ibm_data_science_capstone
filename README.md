# SpaceX Launch Records Dashboard

An interactive dashboard built with Python, Dash, and Plotly to visualize and analyze SpaceX launch data. The dashboard allows users to explore launch success rates, analyze payload performance, and interact with data dynamically.

## Features
- **Launch Site Analysis**: Filter and analyze launch success rates by individual sites or across all SpaceX launch sites.
- **Payload Mass Correlation**: Explore the relationship between payload mass and launch success through an interactive scatter plot.
- **Interactive Visualizations**:
  - Pie Chart: Displays the success distribution of launches by site.
  - Scatter Chart: Visualizes the correlation between payload mass and launch success.
- **Dynamic Data Filtering**: Use dropdowns and range sliders to filter data and update visualizations in real time.

## Technologies Used
- **Python**: Core programming language.
- **Dash**: Framework for building interactive web applications.
- **Plotly**: Library for creating interactive and dynamic visualizations.
- **Pandas**: Data manipulation and analysis.

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/kudzie99/spacex-launch-dashboard.git
   cd spacex-launch-dashboard
Install the required dependencies:

pip install -r requirements.txt
Ensure the dataset (spacex_launch_dash.csv) is in the project directory.

Run the application:

python app.py
Open your browser and navigate to:

http://127.0.0.1:8050/
Dataset
The dashboard uses the SpaceX launch data provided in the spacex_launch_dash.csv file, which contains:

Launch Site
Payload Mass (kg)
Success/Failure (class)
Booster Version Category

How It Works

Launch Site Dropdown:
Select "All Sites" to view data aggregated across all launch sites.
Select a specific site to analyze its success and failure rates.

Payload Range Slider:
Adjust the range to filter data based on payload mass.

Visualizations:
Pie Chart: Shows the total successful launches per site or success vs. failure for a selected site.
Scatter Chart: Displays the correlation between payload mass and launch outcomes, categorized by booster version.

Dashboard Overview
Pie Chart

Scatter Chart

Future Enhancements
Add additional filters, such as launch year or booster type.
Include more detailed data visualizations, such as bar charts and time-series analysis.
Deploy the application on a cloud platform (e.g., Heroku or AWS).

Contributing
Contributions are welcome! Please submit a pull request or open an issue for suggestions and improvements.

Contact
For any questions or feedback, please contact:

Name: [Kudzai]
Email: [kudzaikaremb@gmail.com]
GitHub: https://github.com/kudzie99
