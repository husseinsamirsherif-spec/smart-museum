## 🔌 Pin Mapping & Wiring Table

| Component | Component Pin | Arduino Pin | Description / Notes |
| :--- | :--- | :--- | :--- |
| **LCD I2C (16x2)** | VCC | **5V** | Power supply |
| | GND | **GND** | Ground |
| | SDA | **A4** | Serial Data Line |
| | SCL | **A5** | Serial Clock Line |
| **Ultrasonic (HC-SR04)** | VCC | **5V** | Power supply |
| | GND | **GND** | Ground |
| | Trig | **Pin 8** | Trigger output |
| | Echo | **Pin 9** | Echo input |
| **Servo Motor (Gate)** | VCC (Red) | **5V** | Servo power |
| | GND (Brown/Black) | **GND** | Servo ground |
| | Signal (Orange/Yellow) | **Pin 10** | PWM Signal pin |
| **Keypad (4x4 Matrix)** | Rows (R1, R2, R3, R4) | **Pins 4, 5, 6, 7** | Keypad Row pins |
| | Columns (C1, C2, C3, C4) | **Pins 13, A1, A2, A3** | Keypad Column pins |
| **Indicators & Alarm** | Red LED (+) | **Pin 2** | Security Alarm LED |
| | Green LED (+) | **Pin 3** | Safe / Normal Status LED |
| | Buzzer (+) | **Pin 11** | Alarm Buzzer |
| | White LED (+) | **Pin 12** | Display Spotlight LED |
| | All (-) Terminals | **GND** | Connect through 220Ω resistors |
| **Light Sensor (LDR)** | Pin 1 | **5V** | Power |
| | Pin 2 | **Pin A0** | Analog input *(10kΩ pull-down to GND)* |

---

## 🛠️ Components List

- **Arduino Uno / Nano**
- **16x2 LCD Display with I2C Adapter**
- **HC-SR04 Ultrasonic Distance Sensor**
- **4x4 Matrix Keypad**
- **SG90 Micro Servo Motor**
- **LDR Light Sensor** + 10kΩ Resistor
- **LEDs** (Red, Green, White) + 220Ω Resistors
- **Active / Passive Buzzer**
