# Habit-Tracker-Using-Java
# 📌 Habit Tracker (Java + JSON + CLI)

A simple **habit tracking application** built in Java that lets you **add, modify, delete, and track habits** with real-time progress updates.  
Designed to demonstrate **OOP, JSON persistence, and CLI**.

---

## 🚀 Features

- ✅ Add, modify, delete, and list habits  
- ⏳ See time left until the next habit (no negative times)  
- 📊 Progress tracking with completion percentage (`2/3 habits → 67%`)  
- 💾 JSON-based storage (your data is persistent between runs)  
- 📈 CLI-based bar chart for progress visualization  


---

## 🛠️ Tech Stack

- **Java (OOP, Collections, LocalDateTime, Duration)**  
- **JSON (file persistence)**  
- **CLI (menu-driven interface

---

## 📂 Project Structure
Habit-Tracker/  
── Main.java # Entry point (menu-driven CLI)  
── HabitManager.java # Manages all habits   
│── HabitsActions.java # Habit class with actions  
│── habits.json # Stores all habits persistently  
│── README.md # Project documentation  


---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Hacke4/habit-tracker.git
   cd habit-tracker
2.Compile and run:

```bash
   javac Main.java
   java Main
```
3.Usage
When you run the program, you’ll see a menu like this:

```bash
1. Add Habit  
2. Modify Habit  
3. Delete Habit  
4. View Habits  
5. Exit 
```

Example habit list output:  
```bash

1. ✅Done  Exercise at 05:00 | Time left: -15 hrs -42 min [Today]  
2. ❌Not Done  Lunch at 14:00 | Time left: -6 hrs -42 min [Today]  
3. ❌Not Done  Dinner at 21:00 | Time left: 0 hrs 17 min [Today]  

Progress: 1/3 habits completed (33%)
```



 













