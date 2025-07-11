# 🎮 8x8 MATRIX LED SNAKE GAME

An interactive Snake Game built on an **8x8 LED matrix**, controlled via a **joystick** and with adjustable speed using a **potentiometer**. Designed and developed by **Mohammed Shehsin Thamarachalil Abdulresak**.

---

## 🕹️ Project Description

This project implements a real-time snake game on an 8x8 MAX7219-based LED matrix using an Arduino Nano. Players control the snake using a joystick and adjust speed dynamically via a potentiometer.

---

## 📷 Preview

<p align="center">
  <img src="./img/WhatsApp%20Image%202025-07-11%20at%2019.38.31_32dcbd89.jpg" alt="Snake Game Demo" width="280"/>
</p>

---

## 🔌 Hardware Connections

| Component           | Arduino Nano Pin |
|--------------------|------------------|
| Joystick X-axis    | A2               |
| Joystick Y-axis    | A3               |
| Joystick VCC       | A1 (set to HIGH) |
| Joystick GND       | A0 (set to LOW)  |
| Potentiometer      | A5               |
| MAX7219 DIN        | A1               |
| MAX7219 CS         | A0               |
| MAX7219 CLK        | D10              |

> 📝 **Note:** Joystick power pins are connected to analog pins A0 and A1, used as digital output to make compact side mounting.

---

## ⚙️ Features

- Snake movement in all directions using a joystick  
- Food generation and collision logic  
- Adjustable snake speed via a potentiometer  
- Win and Game Over message animations  
- Dynamic scoring and visual messages using LED patterns  
- Edge wrap-around movement logic  

---

## 🧠 Technologies Used

- Arduino (Nano)  
- C++ (AVR)  
- MAX7219 LED Matrix  
- Joystick and analog reading  
- Matrix display logic with `LedControl` library  

---

## 🗂 Code Structure

- `setup()` initializes the LED matrix and calibrates the joystick.  
- `loop()` handles food generation, input scanning, game state updates.  
- Game mechanics are modularized:  
  - `generateFood()`  
  - `scanJoystick()`  
  - `calculateSnake()`  
  - `handleGameStates()`  
  - `showGameOverMessage()`, `showScoreMessage()`, etc.

---

## ▶️ How to Run

1. Connect components as per the connection table.  
2. Upload the code using Arduino IDE.  
3. Power the Nano and play using the joystick.  
4. Adjust the speed using the potentiometer.  

---

## 📂 Repository

Explore the full code and images [on GitHub](https://github.com/Mohammed-Shehsin/8x8-MATRIX-LED---SNAKE-GAME-MOUDLE).

---
