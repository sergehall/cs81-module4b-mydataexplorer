# CS81 Module 4B – My Personal Data Objects

This project is part of **Module 4 Assignment 4B** for Santa Monica College's CS81 JavaScript Programming course.  
It focuses on analyzing personal weekly data using JavaScript objects and arrays. The assignment involves writing prediction comments, building analytical functions, and reflecting on the process using real-life data.

---

## Repository Structure

```
.
├── myDataJournal.js      # Main JavaScript file with weekly data and analysis functions
├── testDataJournal.js    # Console-based test runner that logs outputs of all functions
├── REFLECTION.md         # Final reflection with answers to assignment questions
└── README.md             # Project overview and usage instructions
```

---

## Requirements

- Node.js installed (v14 or higher recommended)
- Git (for version tracking and pushing to GitHub)

---

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/sergehall/cs81-module4b-mydataexplorer
cd cs81-module4b-mydataexplorer
```

2. **Install Node.js** (if not already installed)

Download from: https://nodejs.org

3. **Run the test file to analyze personal data**

```bash
node testDataJournal.js
```

This script will evaluate and display patterns based on your weekly data (sleep, mood, caffeine, focus, etc).

---

## Functions Included

- `findHighestScreenTime(data)` – Identifies the day with the most screen time
- `averageSleep(data)` – Calculates average sleep over the week
- `mostFrequentMood(data)` – Finds the most common mood
- `correlateCaffeineToFocus(data)` – Analyzes if caffeine improves focus
- `bestSleepDay(data)` – Finds the day with the longest sleep
- `averageFocusPerMood(data)` – Shows average focus level by mood
- `totalCaffeine(data)` – Calculates total caffeine consumption in a week

Each function is:
- Based on real or realistic personal data
- Built with JavaScript loops, arrays, and objects
- Tested using `testDataJournal.js`

---

## What This Assignment Covers

- JavaScript arrays and objects in real-world structure  
- Writing and calling functions with structured data  
- Using object methods and statistical analysis  
- Reflecting on patterns in your own behavior  
- Git & GitHub version tracking and commit practice  

---

## Submission Requirements

- [x] `myDataJournal.js` — includes all data, predictions, and functions
- [x] `testDataJournal.js` — console log output of each function
- [x] `REFLECTION.md` — written reflection based on assignment prompts
- [x] At least **4 meaningful Git commits** with descriptive messages
- [x] Public GitHub repository named: `cs81-module4b-mydataexplorer`

---

## License

This project is for educational purposes only as part of Santa Monica College's CS81 coursework.