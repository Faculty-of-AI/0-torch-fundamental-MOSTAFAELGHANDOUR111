---

🖼️ Project Preview

«Add images or videos of your project here (Car + Glove)»

Example:

![Car](images/car.jpg)
![Glove](images/glove.jpg)

---

📂 Project Structure

├── TX (Glove Code)
│   └── gesture_transmitter.ino
│
├── RX (Car Code)
│   └── robot_receiver.ino
│
├── images
│   ├── car.jpg
│   └── glove.jpg
│
└── README.md

---

⚙️ Installation & Setup

1️⃣ Requirements

- Arduino IDE
- ESP8266 Board Package installed

2️⃣ Install Libraries

Make sure to install:

- Adafruit MPU6050
- Adafruit Sensor
- ESP8266WiFi
- espnow
- Servo

---

3️⃣ Upload Code

🧤 Transmitter (Glove)

- Connect NodeMCU
- Upload TX code
- Note MAC Address

🚗 Receiver (Car)

- Replace MAC Address in TX code
- Upload RX code

---

📡 ESP-NOW Configuration

- Both boards must be in Station Mode
- Use correct MAC Address
- No internet or router required

---

🧪 Testing

1. Power both modules
2. Tilt your hand
3. Observe car movement
4. Place obstacle → verify avoidance

---

⚠️ Troubleshooting

❌ Car not responding

- Check MAC address
- Ensure ESP-NOW initialized
- Same baud rate

---

❌ Motors not working

- Check L298N connections
- Verify battery voltage
- Ensure ENA/ENB connected

---

❌ Servo not moving

- Use external 5V supply
- Check signal pin (D0)

---

🔐 Safety Notes

- Do not power servo directly from NodeMCU if unstable
- Ensure proper grounding
- Avoid short circuits

---

🌍 Applications

- Robotics systems
- Smart control interfaces
- Assistive technology
- IoT-based automation

---

⭐ Contribution

Feel free to fork, improve, and submit pull requests!

---

📜 License

This project is open-source and free to use for educational purposes.