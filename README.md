# Wildtracks – Android App

## 📱 Overview

This repository contains the Android Studio project developed as part of the *Informatik 2* module during the Winter Semester 2024/25.  
The aim of this project was to design and implement an **interactive, child-friendly mobile application** that guides young users through a fictional animal rally in the **Wildpark Grafenberg, Düsseldorf**.

The app combines learning, storytelling, and play — allowing children to discover animals, read fun facts, and test their knowledge in short quizzes.  
All code and UI components were created **from scratch** using Android Studio, **Java**, **Kotlin**, and **XML-based layout design**.

---

## 🎯 Key Objectives

### 🧩 User Interface Design
- Create a clean, engaging, and accessible UI for children.
- Implement all layouts in **XML** with large buttons, soft color palettes, and friendly fonts.
- Use custom drawable resources (icons, animal images, map backgrounds) to maintain a nature-themed aesthetic.

### 🗺️ Application Structure
- Develop multiple **Activity classes** for modular navigation:
  - Home Screen
  - Map View
  - Animal Information Pages
  - Quiz Screen
  - Data Privacy Page
- Connect all screens using **explicit Intents** in Kotlin for smooth user flow.

### 🦌 Interactive Learning Features
- Display educational stories and facts for animals such as **deer, raccoon, and wild boar**.
- Implement a **multiple-choice quiz** on each animal page with scoring logic.
- Offer visual feedback for correct/incorrect answers.

### 🧒 Child-Focused Experience
- Use bright, nature-inspired colors (greens, yellows, browns).
- Large, touch-friendly buttons for easy navigation.
- Clear and minimal text for readability and focus.
- Safe and offline-friendly operation with no data collection.

---

## ⚙️ Core Features

### 🧭 Multi-Activity Navigation
Each major part of the app (Home, Map, Animals, Quiz) is implemented as a separate Activity for modularity and maintainability.

### 🧠 Quiz System
Simple quizzes reinforce learning. Correct answers reward the user with points or animations.

### 🎨 Custom UI Design
Every visual component (buttons, backgrounds, and icons) was designed manually using **XML layouts** and **drawable resources**.

### 📂 Local Asset Integration
Animal icons, map backgrounds, and all text content are stored locally in the project’s **res/drawable** and **assets** directories, ensuring full offline usability.

### 🔒 Data Privacy
A dedicated “Datenschutz” section explains data handling in simple, child-appropriate language.

---

## 🧰 Technologies Used

| Category | Technology |
|-----------|-------------|
| Programming Languages | **Java**, **Kotlin** |
| UI Design | **XML Layouts** |
| IDE | **Android Studio** |
| Build System | **Gradle** |
| Version Control | **Git & GitHub** |
| Target Platform | **Android 8.0 (API 26)** and higher |
| Testing Devices | Android Emulator & physical Android smartphone |

---

## 🚀 Getting Started

### Prerequisites
- Android Studio **(Electric Eel or newer)**
- Git installed
- Android Emulator or physical device (API 26+)

### Installation

```bash
# Clone the repository
git clone https://github.com/ManuelCavaleiro/Wildtracks.git
```

1. Open Android Studio  
2. Go to **File > Open** and select the project folder  
3. Wait for Gradle to sync  
4. Click **Run ▶️** to install on emulator or connected device  

---

## 🎮 Usage

1. Launch the app on your device  
2. Tap **“Start Tier-Rallye”** on the home screen  
3. Explore the map and tap on animal icons
4. Read short animal stories and fun facts  
5. Start the quiz to test your knowledge and collect points   

---

## 🌟 Project Highlights

- 100% self-developed without templates or external libraries  
- Designed for children – intuitive, colorful, and educational  
- Clear separation of logic (Java/Kotlin) and layout (XML)  
- Fully functional offline  
- Focus on **playful learning through exploration**  

---

## 🔮 Future Enhancements

- Add sound effects and animations for higher engagement  
- Expand the animal selection and quiz variety  
- Implement progress tracking and achievement badges  
- Translate app content into multiple languages  
- Introduce GPS-based interaction with real Wildpark Grafenberg map  

---

## 🏆 Credits

Developed by **[Manuel Cavaleiro, German Shaipov, Kathrin Heller und Jana Petry]**  
as part of the *Informatik 2 – Wintersemester 2024/25* module.

