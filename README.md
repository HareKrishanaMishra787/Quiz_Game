# 🧠  Quiz_Game

Welcome to **Quizzler**, a fun and interactive Python-based trivia quiz game that tests your knowledge with real-time questions fetched from the [Open Trivia Database](https://opentdb.com/)! This project was created as part of a 6-month internship program focused on data handling, automation, and Python development.  <br>


<img src = "https://github.com/user-attachments/assets/cf1536fd-ee69-4d15-a026-942c8d9b0acd" width = "300">
<img src = "https://github.com/user-attachments/assets/5636c483-15d9-4ae2-a1ab-2f27bfd1909d" width = "300">

## 🚀 Features

- ✅ Fetches live trivia questions from an API
- 🧠 Interactive True/False quiz format
- 📊 Dynamic scoring system
- 🎨 Clean and user-friendly GUI built with `Tkinter`
- 🔄 Real-time feedback on answers (Green for correct, Red for incorrect)
- 🔧 Uses Python OOP concepts and API integration
- 📦 Cleanly modularized using custom-built classes

## 🛠 Tech Stack

- **Language:** Python
- **Libraries:**  
  - `requests` – API handling  
  - `tkinter` – Graphical User Interface  
  - `html` – Decoding HTML entities  
  - `PIL` (optional for image handling)  
- **Tools:**  
  - Git & GitHub for version control  
  - Open Trivia Database (API source)

## 📁 Project Structure

```
├── main.py               # Main execution script
├── data.py               # Fetches trivia questions via API
├── question_model.py     # Data model for individual questions
├── quiz_brain.py         # Core logic for quiz progression
├── ui.py                 # Tkinter-based UI implementation
└── images/               # Folder containing true/false button images
```

## 🧩 How It Works

1. **Fetch Questions:** The app calls the Open Trivia DB API and retrieves 10 Boolean-type questions.
2. **Question Model:** Each question is stored as an object with its text and answer.
3. **Game Engine:** The `QuizBrain` class handles question flow, scoring, and checking answers.
4. **User Interface:** `Tkinter` GUI presents questions, score, and real-time feedback with colored backgrounds.

## 🖼 UI Preview

> Here's how the app looks in action:  
(*Add screenshot if possible*)

## ✅ Requirements

Make sure you have Python 3.x installed. Install required libraries if necessary:

```bash
pip install requests
```

> Note: `Tkinter` is pre-installed with most Python distributions.

## ▶️ Run the Project

```bash
python main.py
```

Make sure you have the `images` folder containing `true.png` and `false.png` in the same directory.

## 🧠 Learnings & Highlights

- Hands-on experience with data collection, cleaning, and processing
- Building efficient data pipelines and UI systems
- Improved problem-solving, logical thinking, and code optimization
- Learned collaborative workflows using Git and proper documentation practices

## 📬 Feedback

If you enjoyed the project or have suggestions, feel free to open an issue or drop a ⭐ on the repository!
