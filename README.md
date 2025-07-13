🌤️ Weather App – Real-time Weather Forecasting Web App
This is a simple and elegant weather web app that allows users to search for real-time weather information by city name. It displays temperature, humidity, wind speed, and dynamic weather icons based on current conditions.

🔧 Features
🌇 City Search – Get live weather data by entering any city name

🌡️ Temperature Display – Real-time temperature shown in °C

💧 Humidity & Wind Speed – Clean UI with visual indicators

🌤️ Dynamic Weather Icons – Icons change based on weather (clear, clouds, rain, etc.)

❌ Error Handling – Invalid city names show an error message

🎯 Responsive Design – Fits both desktop and mobile screens

🧑‍💻 Technologies Used
HTML5	Webpage structure
CSS3	Styling and layout
JavaScript	Functionality and API integration
OpenWeatherMap API	Real-time weather data fetch

📁 Project Structure
bash
Copy
Edit
Weather-App/
│
├── index.html           # Main HTML file
├── style.css            # CSS styling
├── script.js (inline)   # JavaScript for functionality
└── images/              # Weather icons (rain.png, clear.png, clouds.png, etc.)
🖼️ Weather Icons Used
Make sure these image files are inside the images/ folder:

clear.png

clouds.png

rain.png

drizzle.png

mist.png

humidity.png

wind.png

search.png

🔑 API Used
OpenWeatherMap API
Base URL:

text
Copy
Edit
https://api.openweathermap.org/data/2.5/weather?units=metric&q={city name}&appid={API_KEY}
Replace {API_KEY} with your actual key. You can get it for free from:
👉 https://openweathermap.org/api

🚀 How to Run Locally
Clone this repo or download the files.

Open the folder in any code editor (e.g., VS Code).

Replace your API key in the script section of index.html:

javascript
Copy
Edit
const apiKey = "your_api_key_here";
Open index.html in your browser.

Enter a city name and click the search icon!

📌 Future Scope (Optional Enhancements)
🌍 Auto location-based weather using geolocation

🔔 Weather alert notifications

🙏 Acknowledgements
Weather data powered by OpenWeatherMap

Icon design credits: Freepik/Flaticon (if applicable)

📷 Demo Screenshot (Optional)
