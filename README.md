# 🤖 Robot Line Follower with PID Control  

A **robot line follower** is an autonomous vehicle that follows a predefined path, typically a black line on a white surface. This project implements a **PID controller** for optimized movement, combining both **hardware** and **software simulations** to ensure stable and accurate performance.  

---

## ✨ Features  
- 🚗 Autonomous navigation using sensors and a microcontroller  
- ⚡ PID control for smooth and accurate line tracking  
- 🔧 MATLAB & Simulink simulation for controller tuning  
- 🔩 Hardware implementation with motors and sensors  
- 📊 Step response analysis (rise time, overshoot, settling time)  

---

## 🛠️ Components & Tools  
### Hardware  
- Microcontroller  
- Infrared/optical sensors  
- Motors & wheels  
- Robot chassis  
- Power supply  

### Software  
- **MATLAB/Simulink** (PID tuning & transfer function analysis)  
- Transfer function modeling & step response plotting  

---

## ⚙️ Methodology  
1. Sensors detect the contrast between the line and the surface.  
2. Data is sent to the microcontroller.  
3. A **PID controller** adjusts motor speed and direction to stay on track.  
4. MATLAB/Simulink is used to model and validate the system’s closed-loop performance.  

---

## 📊 Results  
- **PID Gains**:  
  - Kp = 0.12  
  - Ki = 0.1  
  - Kd = 0.02  

- **Closed-Loop Response**:  
  - Rise Time ≈ 0.95 s  
  - Overshoot ≈ 2.5%  
  - Settling Time ≈ 2.9 s  

Both hardware and software experiments yielded consistent results, confirming the system’s stability and efficiency.  

---

This project is for **academic and educational purposes**.  
Feel free to use and adapt for learning and research.  
