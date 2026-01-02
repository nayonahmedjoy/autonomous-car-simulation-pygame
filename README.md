# 🚗 Autonomous Car Driving Simulation (Pygame)

A simple **autonomous car driving simulation** built using Python and Pygame.  
This project demonstrates how a car can automatically navigate a predefined track using **pixel-based sensing and rule-based decision logic**.

---

## 🚀 Project Overview

This simulation mimics a basic self-driving car system where:
- The car follows a road track automatically
- Direction changes are based on pixel color detection
- A virtual sensor (camera point) checks the path ahead
- The car turns left/right/up/down depending on track layout

This project focuses on **logic, simulation, and computer-vision-inspired techniques**, not machine learning.

---

## 🧠 How It Works

1. The car moves on a track image
2. A virtual camera checks pixels around the car
3. White pixels (`RGB = 255`) represent valid road
4. If the road ends, the car changes direction
5. The car rotates and adjusts camera offsets dynamically

---

## 🛠️ Technologies Used

- **Python**
- **Pygame**
- **2D Simulation**
- **Rule-based decision logic**
- **Pixel color detection**
- **Linux environment**

---

## 📁 Project Structure

```
autonomous-car-simulation/
│
├── main.py          # Main simulation code
├── track6.png       # Track image
├── tesla.png        # Car sprite
├── README.md        # Project documentation
└── .gitignore
```

---

## ▶️ How to Run the Project

### 1️⃣ Install dependencies
```bash
pip install pygame
```

### 2️⃣ Run the simulation
```bash
python main.py
```

Make sure the image files (`track6.png`, `tesla.png`) are in the same directory.

---

## 🎯 Purpose of This Project

- Understand basic autonomous driving logic
- Learn pixel-based sensing techniques
- Practice Pygame for simulations
- Build a strong computer-vision-style portfolio project

---

## 🔮 Future Improvements

- Add collision detection
- Implement speed control
- Add multiple sensor points
- Integrate AI or reinforcement learning
- Support multiple tracks

---

## 📜 License

This project is open-source and created for educational and portfolio purposes.

---

## 🙌 Author

**Nayon Ahmed**  
Linux user | Python developer | Simulation enthusiast  
GitHub: https://github.com/nayonahmedjoy
