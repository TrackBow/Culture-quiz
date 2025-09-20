# 🧠 Track Quiz - A Python Quiz Game with Tkinter

Track Quiz is a comprehensive quiz game developed in Python, featuring a graphical user interface built entirely with the Tkinter library. This project was designed to practice several key application development concepts: creating user interfaces, managing external data, and data persistence.

## 🎥 Demonstration

<img width="797" height="662" alt="image" src="https://github.com/user-attachments/assets/52aca5d3-919d-4e66-9621-7cb8e7bacd5d" />
<img width="784" height="669" alt="image" src="https://github.com/user-attachments/assets/703583a7-359b-44c8-9c61-e7e081fa4473" />
<img width="778" height="673" alt="image" src="https://github.com/user-attachments/assets/b8d8d838-6b7e-4a03-b7a8-eb150f40cd66" />

---

### ✨ Key Features

*   **Intuitive GUI:** A clean and responsive user interface built with **Tkinter**, organized into multiple "pages" (Menu, Game, Scoreboard).
*   **External Data Loading:** The quiz dynamically loads all questions from a `questions.csv` file, separating data from the source code.
*   **Multi-type Question Support:** Handles both purely textual questions and **image-based** questions (thanks to the Pillow library).
*   **Theme System:** Questions can be filtered by theme via a dropdown menu, allowing for specialized quizzes.
*   **Score Persistence:** High scores are automatically saved to a `scoreboard.json` file. The leaderboard is maintained and sorted for each theme individually.
*   **Flexible Answer Validation:** The verification system accepts multiple variations of the correct answer (e.g., "Victor Hugo|hugo") and is not case- or space-sensitive.

---

### 🛠️ Technologies Used

<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Tkinter-GUI_Toolkit-FFD43B?style=for-the-badge" alt="Tkinter"/>
  <img src="https://img.shields.io/badge/Pillow-Image_Processing-9747FF?style=for-the-badge" alt="Pillow"/>
</div>

*   **Python 3** for the program logic.
*   **Tkinter** for the entire graphical user interface.
*   **Pillow (PIL Fork)** to load, resize, and display question images.
*   Standard modules **CSV** (to read questions) and **JSON** (to manage the scoreboard).

---

### 🚀 How to Run the Project

**1. Prerequisites**
*   Make sure you have **Python 3** installed on your machine.

**2. Clone the Repository**
cd your-project-name
python quiz.py

or use .exe
