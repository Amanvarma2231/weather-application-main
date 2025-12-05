# 🌤️ Weather Application

<div align="center">

  [![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/downloads/)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()


*A modern, user-friendly weather application built with Python and Tkinter that provides real-time weather information for any city worldwide.*


</div>

<table>
<tr>
<td><img src="sc/sc_1.png" alt="Weather App Screenshot 1" width="400"></td>
<td><img src="sc/sc_2.png" alt="Weather App Screenshot 2" width="400"></td>
</tr>
</table>

## ✨ Key Features

### 🌡️ Weather Information
- Real-time weather data display
- Current temperature and conditions
- Detailed weather metrics:
  - Humidity
  - Wind speed and direction
  - Atmospheric pressure
  - Visibility
  - Sunrise and sunset times
  - "Feels like" temperature

### 📊 Advanced Features
- 5-day weather forecast with detailed predictions
- Dynamic weather icons that change based on conditions
- Dynamic background colors reflecting current weather
- Excel-based weather data logging system
- Date and time display with automatic updates
- User-friendly interface with intuitive controls

## 🛠️ Technical Requirements

### System Requirements
- Python 3.8 or higher
- Active internet connection
- OpenWeatherMap API key
- 100MB free disk space
- 4GB RAM recommended

### Dependencies
- `requests==2.31.0`
- `pandas==2.1.0`
- `openpyxl==3.1.2`
- `Pillow==10.0.0`
- `python-dateutil==2.8.2`
- `numpy==1.24.3`

## 📥 Installation Guide

1. **Clone the Repository**
   ```bash
   git clone https://github.com/sabbirahmad12/weather-application.git
   cd weather-application
   ```

2. **Set Up Virtual Environment**
   ```bash
   # Create virtual environment
   python -m venv venv

   # Activate virtual environment
   # For Windows:
   venv\Scripts\activate
   # For Linux/Mac:
   source venv/bin/activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## ⚙️ Configuration

1. **Get OpenWeatherMap API Key**
   - Visit [OpenWeatherMap](https://home.openweathermap.org/users/sign_in)
   - Create a free account
   - Navigate to your account dashboard
   - Generate an API key
   - Replace `API_KEY` in `main.py` with your key

## 📁 Project Structure
```
weather_app/
├── data/                  # Excel logs and data storage
├── main.py                # Main application file
├── background_manager.py  # Background color management
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
└── sc/                    # Application screenshots
```

## 🚀 Usage Guide

1. **Launch the Application**
   ```bash
   python main.py
   ```

2. **Using the Application**
   - Enter city name in the search box
   - Click "Get Weather" or press Enter
   - View current weather and forecast
   - Check Excel logs in the data folder

## 📊 Data Logging

The application automatically logs weather data to Excel files:
- Location: `data/weather_logs.xlsx`
- Logged Information:
  - Timestamp
  - City name
  - Temperature
  - Weather conditions
  - Humidity
  - Wind speed
  - Pressure
  - Visibility

## ⚠️ Important Notes

- Ensure stable internet connection for real-time updates
- Keep your API key secure and don't share it
- Weather data updates every 5 minutes
- Excel logs are stored in the data folder
- Application requires Python 3.8 or higher

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

👤 Author & Contact

Aman Varma

GitHub: @Amanvarma2231

Project Link: https://github.com/Amanvarma2231/weather-application-main

## 🌟 Star and Fork 🚀


## Support Me ❤️

<div align="center">
  
  Thanks for visiting!
  🚀 How to Use
Launch the Application:

bash
python main.py
Get Weather:

Type a city name (e.g., "London", "Tokyo") into the search box.

Click the "Get Weather" button or press Enter.

View the current weather and a 5-day forecast in the main window.

View Logs: All searched weather data is automatically saved to data/weather_logs.xlsx. You can open this file with any spreadsheet software (like Microsoft Excel or Google Sheets).

🛠️ Project Structure
text
weather-application-main/
├── data/                    # Directory for Excel log files
├── sc/                     # Directory for application screenshots
├── background_manager.py   # Handles dynamic background color logic
├── main.py                # Main application script and GUI
├── requirements.txt       # Python package dependencies
└── README.md             # This file
📋 Dependencies
This project relies on the following key Python libraries:

Package	Version	Purpose
requests	~2.31.0	Makes HTTP calls to the OpenWeatherMap API.
pandas	~2.1.0	Manages and writes weather data to Excel logs.
openpyxl	~3.1.2	Enables pandas to read/write Excel .xlsx files.
Pillow (PIL)	~10.0.0	Handles weather icon images within the Tkinter GUI.
(See requirements.txt for the complete list.)

🤝 Contributing
Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated .

If you have a suggestion to improve this project:

Fork the repository.

Create a feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

Please ensure your code follows the existing style for consistency.

📄 License
Distributed under the MIT License. This means you are free to use, modify, and distribute the software, provided the original license and copyright notice are included. See the LICENSE file for more details.

👤 Author & Contact
Aman Varma

GitHub: @Amanvarma2231

Project Link: https://github.com/Amanvarma2231/weather-application-main

For questions, feedback, or support, please open an Issue on the GitHub repository.

⭐ Support the Project
If you found this project helpful or interesting, please consider giving it a Star on GitHub! It helps others discover the project.

text

  


