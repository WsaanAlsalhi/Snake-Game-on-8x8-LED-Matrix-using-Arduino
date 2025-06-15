#  Snake Game on 8x8 LED Matrix using Arduino

This project is a classic **Snake Game** implemented on an **8x8 LED Matrix** using an **Arduino** and a **joystick** for control. The snake grows when it eats the food and restarts if it collides with itself.

---

##  Features

- Snake movement controlled by joystick (analog input)
- Food appears randomly on the grid
- Snake grows in length after eating food
- Collision detection with snake's own body
- LED matrix updated using multiplexing
- Blinking food effect

---

##  Components Required

| Component              | Quantity |
|------------------------|----------|
| Arduino Uno/Nano       | 1        |
| 8x8 LED Matrix (Cathode or Anode) | 1 |
| Joystick Module        | 1        |
| Jumper Wires           | 1 pack   |
| Breadboard (optional)  | 1        |

---

##  Pin Configuration

### LED Matrix:

| Matrix Part | Arduino Pins        |
|-------------|---------------------|
| Rows (Y1–Y8)| D9, D10, D11, D12, A3, A0, A1, A2 |
| Columns (X1–X8)| D13, D2, D3, D4, D5, D6, D7, D8 |
