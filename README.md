# AI-Vehicle-Copilot
 AI-powered Smart Driver Assistance &amp; Vehicle Safety Monitoring System using Python, OpenCV, MediaPipe, TensorFlow Lite, ESP32, and Blynk IoT. Detects driver drowsiness, yawning, engine overheating, gas leaks, alcohol, rain, obstacles, and seat belt status with real-time multilingual voice alerts and a live IoT dashboard.

## Features

- Driver Drowsiness Detection
- Yawning Detection
- Engine Temperature Monitoring
- Multilingual Voice Alerts (English, Hindi & Tamil)
- Real-Time Blynk Dashboard
- ESP32 Wi-Fi Communication
- Instant Audio & Dashboard Alerts

---

## Technologies Used

### Programming
- Python
- C++ (Arduino)

### AI & Computer Vision
- OpenCV
- MediaPipe
- TensorFlow Lite

### IoT & Embedded
- ESP32
- Blynk IoT
- Arduino IDE

### Python Libraries
- Flask
- OpenCV
- NumPy
- gTTS
- playsound
- pyserial

---

## Hardware Used

- ESP32 Development Board
- USB Camera
- Temperature Sensor
- Buzzer
- Jumper Wires
- Breadboard

---

## Project Structure

```text
project/
│── app.py
│── voice.py
│── detect_fault.py
│── templates/
│── static/
│── model/
│── Arduino/
│── requirements.txt
│── README.md
```

---

## How It Works

1. ESP32 reads data from all vehicle sensors.
2. Sensor values are sent to the Python application through Wi-Fi.
3. The camera continuously monitors the driver's face.
4. AI detects drowsiness and yawning.
5. The system analyzes all sensor values.
6. If a fault is detected:
   - Voice alert is played.
   - Dashboard updates instantly.
   - Warning indicators are activated.
7. The system returns to normal once the fault is cleared.

---

## Detected Faults

| Fault | Detection |
|--------|-----------|
| Driver Drowsiness | AI Vision |
| Yawning | AI Vision |
| Engine Overheating | Temperature Sensor |


---

## Supported Languages

- English
- Hindi
- Tamil
- Spanish
- German
- French

Voice alerts automatically change based on the selected language.

---

## Dashboard


- Driver Status
- Fault Status
- Alerts
- Vehicle Health Monitoring

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/AI-Driver-Assistance-System.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Upload ESP32 Code

- Open Arduino IDE.
- Select the ESP32 board.
- Update the Wi-Fi credentials.
- Update the Blynk Authentication Token.
- Upload the sketch to the ESP32.

### Run the Project

```bash
python app.py
```

Open your browser and navigate to:

```text
http://localhost:5000
```

---

## Applications

- Smart Vehicles
- Driver Monitoring Systems
- Fleet Management
- Automotive Safety
- Intelligent Transportation Systems
- Road Accident Prevention

---

## Future Enhancements

- GPS Tracking
- Cloud Database Integration
- Mobile Application
- Face Recognition
- Automatic Emergency Calling
- Predictive Vehicle Maintenance

---
