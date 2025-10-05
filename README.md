# cs294-137-hw3-joyce-mdes
cs294-137-hw3: A Real AR Game with ARUCO Marker
###Links:
- Unity Files (my project is over 10GB, so I couldn't upload it to GitHub): https://drive.google.com/file/d/1PbY7AVmQCYNsXz8OUy4basD-T6UWfUVf/view?usp=drive_link
- YouTube Video: https://youtu.be/0WWgxqocUvI

# 🧱 AR Block Shooter  
*A mini Augmented Reality game built with Unity, AR Foundation, and ARUCO marker tracking.*

---

## 📱 Overview
**AR Block Shooter** is a playful AR mini-game that blends physical and digital worlds using image tracking.  
By detecting an **ARUCO marker**, players can spawn a virtual game board on any real surface and start stacking blocks — then shoot balls to knock them down and earn points!

🎯 **Core Features**
- Real-time **AR tracking** with printed ARUCO markers  
- Interactive **block stacking** gameplay  
- Simple **shooting mechanics** with limited ammo (5 shots)  
- Dynamic **score system** based on hits  
- Compatible with **iOS (ARKit)** and **Android (ARCore)** devices  

---

## 🕹️ How to Play
1. **Print** your ARUCO marker (included in the `Assets/Markers` folder).  
2. **Open** the game on your mobile device.  
3. Point your camera at the printed marker — the **blue game board** will appear in AR space.  
4. Tap the buttons at the bottom to **add and stack blocks** (3 shapes available).  
5. Press **Start** to begin the challenge.  
6. **Shoot** up to five balls to knock down the blocks.  
7. Your **final score** will be displayed at the end of the round!  

---

## 🧠 Development Details

| Component | Description |
|------------|-------------|
| **Engine** | Unity 6.2 (6000.2.6f2) |
| **AR Framework** | AR Foundation (ARKit / ARCore) |
| **Language** | C# |
| **Platform** | iOS, Android |
| **Marker Tracking** | ARUCO marker (via Image Tracking) |
| **Render Pipeline** | Universal Render Pipeline (URP) |

---

## 📂 Project Structure
