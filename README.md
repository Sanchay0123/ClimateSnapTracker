# Climate SnapTracker

## Overview
The Climate Snap-tracker is an interactive web application that provides users with global climate visualization tools, real-time weather data, and a sleek, user-friendly interface. Built using Flask as the backend framework and HTML/CSS for the front-end design, the project combines interactivity with dynamic data visualization.

## Features
* **3D Interactive Globe**: Users can explore countries on an interactive globe implemented with Plotly. Clicking on a country redirects users to detailed weather information for that location.
* **Weather Visualization**:
  * Displays real-time weather updates including temperature, wind speed, and wind direction.
  * Provides a temperature forecast with an integrated graph for better understanding trends.
* **Navigation**: Easy navigation through a Home, About, and Contact Us page with a minimalistic and responsive design focusing on usability.
* **Contact Form**: Users can submit feedback or queries via a simple contact form.
* **Custom Styling**: Unique, visually appealing designs for different pages.

## Technology Stack
**Backend**:
* Python
* Flask (Microframework for routing and handling requests)
* Plotly (Interactive geographic maps and 3D globe visualization)
* Requests Library (Fetching data from external APIs)

**Frontend**:
* HTML5
* CSS3
* Responsive design with dynamic elements (Jinja2 Templates)

## API Integration
* **Open-Meteo**: The application interacts with the Open-Meteo API to fetch real-time and forecast weather data based on the latitude and longitude of various cities and countries.

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd ClimateSnapTracker
   ```

2. **Install dependencies**:
   Make sure you have Python installed, then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   Start the Flask server:
   ```bash
   python app.py
   ```

4. **Access the web app**:
   Open your web browser and navigate to `http://127.0.0.1:5000/`.

## Future Enhancements
* Include historical climate data visualization.
* Add user accounts for personalized experiences.
* Add more detailed climate information (such as precipitation and snowfall).
* Database integration for storing feedback and user data.
* Ability to adjust globe size interactively.
