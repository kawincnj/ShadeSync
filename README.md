# ShadeSync — Shade-Aware Route Planning

Computer vision for more comfortable urban walking: U-Net shadow segmentation estimates shade coverage from satellite imagery, and candidate routes are ranked by shade-to-distance ratio.

## Contribution and recognition

Kawin Chamnanchak developed the U-Net shadow-segmentation component using Roboflow and ArcGIS/World Imagery. The project placed sixth nationally at the CMKL AI Innovator Award 2025.

## Repository guide

- `get_data_for_train/`: training-data preparation.
- `models/`: model-related assets.
- `API/`: backend integration.
- `shadesync/`: application components.
- `HowToRun.txt`: existing run notes.

The pipeline is: route candidates → satellite imagery → shadow mask → shade coverage → route ranking. Check the existing run notes and dependency files before starting; installation has not been retested here.

## Imagery and limitations

Retain attribution and comply with ArcGIS/World Imagery, Google Maps, and dataset terms. Satellite imagery and predicted masks may be outdated or inaccurate; route suggestions do not guarantee shade or safe walking conditions.

---

# 🌳 ShadeSync  
### 🏆 CMKL AI Innovator Award 2025 — **6th Place**

**ShadeSync** is a web application that helps users find **cooler walking routes** by prioritizing paths with **more surrounding shade**, helping reduce heat exposure and improve walking comfort in urban environments.

> ☀️ Walking smarter, not shorter.

---

## 🌍 Problem Statement
In hot cities, especially in tropical regions like Thailand, walking outdoors can be uncomfortable and even unsafe due to heat exposure.  
Most navigation apps optimize for **shortest or fastest routes**, but **ignore environmental comfort** such as shade coverage.

---

## 💡 Our Solution
ShadeSync analyzes satellite imagery and AI-based shadow detection to recommend **routes with higher shade coverage**, even if they are slightly longer — because comfort matters.

📊 From our survey:
> **81% of users prefer a longer route with more shade** over a shorter route with less shade.

---

## 🚶‍♂️ How It Works
1. User selects a start and destination point  
2. Multiple walking routes are generated  
3. Satellite imagery is analyzed using an AI model (U-Net)  
4. Shadow coverage along each route is calculated  
5. Routes are ranked based on **shade-to-distance ratio**

---

## 🧠 Key Technologies
- **Python**
- **U-Net (Semantic Segmentation)**
- **Satellite Imagery (ArcGIS / World Imagery)**
- **Google Maps API**
- **Web Application (Frontend + Backend)**

---

## 🧪 AI Model
- Model: **U-Net**
- Task: **Shadow segmentation from satellite images**
- Output: Binary shadow mask
- Evaluation focuses on shadow coverage along walking routes

---

## 🖥️ Application Features
- 🌤️ Shade-aware route selection  
- 🗺️ Multiple route comparison  
- 📏 Distance & time consideration  
- 🌡️ Comfort-focused navigation  

---

## 🎯 Impact
- Encourages walking in hot cities  
- Improves pedestrian comfort  
- Supports urban sustainability  
- Can be extended for:
  - Elderly users
  - Heat-sensitive individuals
  - Smart city planning

---

## 🏅 Achievement
- **CMKL AI Innovator Award 2025**
- **6th Place (National Level)**

---

## 📽️ Presentation
👉 [View Project Slides (Canva)](https://www.canva.com/design/DAG6n_rjz5Q/Fi5WIXlUs-SyLNBpwRmn6Q/view)

---

---

## 🚀 Future Improvements
- Real-time sun position & time-based shadows  
- Mobile application version  
- Integration with weather & temperature data  
- Personalized route preferences  

---

## 📄 License
This project is for educational and research purposes.

---

✨ *ShadeSync — Choose comfort over distance.*

