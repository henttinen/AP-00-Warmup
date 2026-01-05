# AP-00-Warmup: The "Broken" Grade Calculator

**Welcome to Applied Programming!**

This is your first assignment. It is a **Diagnostic Lab** designed to "shake off the rust" after the winter break. It tests your ability to use your development environment (VS Code), read error messages, and write basic Python logic.

## 🏁 The Objective
You have inherited a partial script (`grade_calculator.py`) from a previous developer.
1.  **It is broken.** It contains **3 specific bugs** (Syntax, Logic, and Type errors) that prevent it from running.
2.  **It is incomplete.** Once fixed, you need to add a new feature to ask the user for input.

**Goal:** Fix the code, add the feature, and push your changes to GitHub.

---

## 🛠️ Setup Instructions

### 1. Create your Repository
1.  Click the green **"Use this template"** button at the top right of this page.
2.  Select **"Create a new repository"**.
3.  Name it: `AP-00-Warmup-MyName` (replace `MyName` with your actual name).
4.  **Important:** Set the visibility to **Private**.
5.  Click **Create repository**.

### 2. Grant Access to me
Since your repository is Private, you must manually give me permission to view it for grading.
1.  Go to your new repository's **Settings** tab.
2.  Click **Collaborators** on the left menu.
3.  Click the **Add people** button.
4.  Type the teacher's username: `henttinen`
5.  Select the user and click **Add to this repository**.

### 3. Clone to VS Code
1.  Open **Visual Studio Code** on your computer.
2.  Open the **Command Palette** (`Ctrl+Shift+P` on Windows, `Cmd+Shift+P` on Mac).
3.  Type `Git: Clone` and select it.
4.  Paste the URL of **YOUR** new repository.
5.  Select a folder on your computer to save it.
6.  Click **Open** when asked to open the cloned repository.

---

## 🐛 Phase 1: Debugging
Open `grade_calculator.py`. Do **not** rewrite the whole file. Try to run it and fix the errors one by one.

### Task 1: Fix the Syntax Error
Run the code (Terminal: `python grade_calculator.py`).

### Task 2: Fix the Logic Error
Once the syntax is fixed, run it again. It will crash.

### Task 3: Fix the Type Error
Once the math works, the program tries to print the result. It will crash again.

---

## 🚀 Phase 2: New Feature
Now that the code runs successfully, you need to add functionality.

**The Requirement:**
Modify the `main()` function to do the following:
1.  Ask the user: *"Enter a new grade (1-5):"*
2.  **Check if the input is valid:**
    * If the number is between 1 and 5, add it to the `student_grades` list.
    * Recalculate and print the **new** average.
    * *Tip:* You will need to convert the user input from a String to an Integer.
3.  **Handle invalid input:**
    * If the user types text (like "hello") or a number outside the range (like "10"), print *"Invalid input."*

---

## 📝 Submission Checklist

Before you submit, verify the following:

- [ ] I have fixed all 3 bugs and the code runs without crashing.
- [ ] My code successfully asks the user for input.
- [ ] If I enter `5`, the average updates correctly.
- [ ] I have committed my changes with a clear message (e.g., "Fixed bugs and added user input").
- [ ] I have pushed my changes to GitHub.
- [ ] **Crucial:** I have added the teacher as a collaborator in the Settings.

### How to Submit
Copy the URL of **your** GitHub repository and submit it to the Moodle assingment.

---

## ❓ Troubleshooting

**"I can't run python in the terminal"**
* Try typing `python3 grade_calculator.py` or `py grade_calculator.py`.
* Ensure you have the Python extension installed in VS Code.

**"The code runs but nothing happens"**
* Did you save the file? (`Ctrl+S` / `Cmd+S`).
* Check your indentations. Python relies on proper indentation to know what is inside the function.