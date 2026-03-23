# Student-attendance-traccking-management
# 📊 StudTracker – Meeting Analytics Dashboard

StudTracker is a Java-based desktop application that analyzes online and offline meeting data and visualizes participant performance using charts and reports.

---

## 🚀 Features

- 📁 Load meeting data from JSON files  
- 👥 Track participant attendance and activity  
- 📊 Generate visual analytics using charts (JFreeChart)  
- 🧮 Calculate participation scores  
- 📝 Generate detailed reports  
- 📴 Supports both **online + offline meetings**

---

## 🛠️ Tech Stack

- **Java (Core + Swing)** – UI and logic  
- **Maven** – Project management  
- **Jackson** – JSON parsing  
- **JFreeChart** – Data visualization  

---

## 📂 Project Structure

```
StudTracker-main/
│── src/main/java/
│   ├── App.java                # Main application (UI + logic)
│   ├── ReportGenerator.java   # Report creation logic
│
│── src/main/resources/
│   ├── meet_data.json
│   ├── meet_data_multi.json
│   ├── meet_data_with_offline.json
│
│── target/                    # Compiled files
│── pom.xml                    # Maven dependencies
│── LICENSE
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone <repo-url>
cd StudTracker-main
```

### 2. Build using Maven
```bash
mvn clean install
```

### 3. Run the Application
```bash
mvn exec:java -Dexec.mainClass="App"
```

OR run directly from IDE (IntelliJ / Eclipse) using `App.java`.

---

## 📊 How It Works

1. Loads meeting data from JSON file  
2. Parses:
   - Participants  
   - Attendance  
   - Chat activity  
   - Session duration  
3. Calculates performance metrics  
4. Displays:
   - Bar charts  
   - Line charts  
   - Participant rankings  

---

## 📈 Output

- Visual charts for meeting analytics  
- Participant engagement scores  
- Attendance tracking  
- Generated report file (`StudTrack_Report.txt`)  

---

## 📝 Sample Data

Data is stored in:
```
src/main/resources/meet_data_with_offline.json
```

You can modify this file to test with custom meeting data.

---

## 🧩 Dependencies (from pom.xml)

- Jackson Databind  
- JFreeChart  

---

## ⚠️ Notes

- Ensure JSON file is present in `resources` folder  
- Requires Java 8 or higher  
- Charts open in a Swing window  

---

## 📌 Future Improvements

- Export reports to PDF  
- Web-based dashboard  
- Database integration  
- Real-time meeting tracking  

---

## 👨‍💻 Author

Developed as a Meeting Analytics Project using Java.

---
