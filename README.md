# US Domestic Airline Flights Performance Dashboard

This project utilises Dash by Plotly to create an interactive dashboard for exploring US domestic airline flights performance based on a provided dataset. Users can visualise various metrics such as flight cancellations, average flight times, delays, and more.

## Installation

To run this dashboard locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dotserver/US-Domestic-Airline-Flights-Performance.git
   cd US-Domestic-Airline-Flights-Performance

2. **Install dependencies:**

It's recommended to use a virtual environment like venv or conda for Python dependency management. Navigate into your project directory and run:

    pip install -r requirements.txt

## Running the Application

After installing the dependencies, you can run the application with the following command:

    python app.py


## Usage

1. **Select Report Type:**

- Choose between "Yearly Airline Performance Report" or "Yearly Airline Delay Report" using the dropdown menu.

2. **Choose Year:**

- Select a specific year from the dropdown menu to view the corresponding data.

3. **Generate Analysis:**

- Click the "Show Analysis" button to generate graphs and visualizations based on your selected options.

4. **Interact with Graphs:**

- Explore different metrics such as monthly flight cancellations, average flight times, delays by airline, and more.

## Features

- **Interactive Graphs:** Visualize data using Plotly's interactive graphing library.
- **Dropdown Menus:** Select specific report types and years for detailed analysis.
- **Loading Indicator:** Provides feedback to users while data is being processed.

## Credits

This project was developed as part of [IBM Developer Skills Network](https://developer.ibm.com/courses/) course on Data Visualization.