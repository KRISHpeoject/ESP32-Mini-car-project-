ESP32 Bluetooth Controlled Car

This project showcases a simple and efficient four-wheel car built using the ESP32 microcontroller, the TB6612FNG motor driver, and two small DC N20 gear motors. The car is fully controlled via Bluetooth using a smartphone.

🔧 Hardware Overview

Microcontroller: ESP32 (with Bluetooth capability)

Motor Driver: TB6612FNG Dual H-Bridge

Motors: 2 × N20 DC gear motors

Front Wheel: using dummy Motor gear box and wheel

Power Supply: 3.7 volt battery 

Motor Driver VM: 3.7-5.0V one Li-ion battery


Bluetooth Communication: Uses BluetoothSerial library

Control Method: Smartphone app or Bluetooth terminal (commands: F, B, L, R, S, 1–4)


📦 Features

Forward / Backward Movement: Both motors run at the same speed

Turning Left / Right: One motor is stopped while the other runs

Stop Command: Both motors stop instantly

Speed Control: 4 levels (100, 150, 200, 255 PWM)


🧠 How It Works

Commands are sent via Bluetooth from the smartphone. The ESP32 receives characters and maps them to motor actions using the TB6612FNG driver.
