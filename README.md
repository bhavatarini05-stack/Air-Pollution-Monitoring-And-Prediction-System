# AI-Based Smart Air Pollution Monitoring and Prediction System using IoT

Overview:
The AI-Based Smart Air Pollution Monitoring and Prediction System is an IoT and AI-powered solution that monitors environmental conditions in real time and predicts future air quality. The system uses IoT sensors to collect pollution data and Machine Learning models to forecast the Air Quality Index (AQI), enabling early warnings and better environmental decision-making.

Features:

- 🌫️ Real-time air quality monitoring
- 🌡️ Temperature and humidity monitoring
- 📊 AQI prediction using Machine Learning
- ☁️ Cloud-based data storage and visualization
- 📱 Remote monitoring through IoT dashboard
- ⚠️ Pollution threshold alerts
- 📈 Historical data analysis and forecasting

Technologies Used:

Hardware:
- ESP32 Microcontroller
- MQ135 Gas Sensor
- DHT11 Temperature & Humidity Sensor
- LCD Display (Optional)

Software:
- Arduino IDE
- Python
- Google Colab / Jupyter Notebook
- ThingSpeak
- Embedded C

Machine Learning:
- Linear Regression
- Decision Tree Regressor
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

System Architecture:

```
MQ135 + DHT11 Sensors
          │
          ▼
       ESP32 Controller
          │
          ▼
   ThingSpeak Cloud
          │
          ▼
 Machine Learning Model
          │
          ▼
AQI Prediction & Dashboard
```

Project Structure:

```
Air-Pollution-Monitoring/
│
├── Arduino_Code/
├── ML_Model/
├── Dataset/
├── Images/
├── Results/
├── README.md
└── requirements.txt
```

Machine Learning Workflow:

1. Collect sensor data
2. Store data in the cloud
3. Preprocess dataset
4. Train ML models
5. Predict AQI
6. Display results on dashboard

Output:

- Real-time Air Quality Monitoring
- Temperature & Humidity Display
- AQI Prediction
- Pollution Trend Analysis
- Alert Generation

Future Enhancements:

- Deep Learning (LSTM) for improved prediction
- Mobile application integration
- PM2.5 & PM10 sensors
- GPS-based pollution mapping
- AI-powered anomaly detection

Author:
Inira
B.Tech Artificial Intelligence & Data Science
