# 🤖 RPA Challenge Automation — UiPath

## 📌 Overview

This project is an automated solution for the **RPA Challenge** using UiPath.
The goal of the challenge is to build a workflow that reads data from an Excel spreadsheet and accurately inputs it into dynamic web form fields whose positions change after each submission.

The automation demonstrates robust selector handling, dynamic UI interaction, and reliable data-driven automation.

---

## 🚀 Features

* Data extraction from Excel file
* Automated web form filling
* Dynamic selector handling (fields change position after each submission)
* Looping through multiple records
* Error handling and workflow stability
* High-speed automated submissions

---

## 🛠️ Technologies Used

* UiPath Studio
* Excel Activities
* DataTables
* Web Automation (UI Automation)
* Dynamic Selectors / Anchor Base techniques

---

## 📂 Project Structure

```
/Main.xaml          -> Main workflow
/Data/Input.xlsx    -> Input data file
/Screenshots        -> Project screenshots
/README.md          -> Documentation
```

---

## ⚙️ How It Works

1. Download the Excel data file.
2. Launch the RPA Challenge webpage.
3. Read all records into a DataTable.
4. Loop through each row:

   * Identify form fields dynamically.
   * Enter corresponding values.
   * Submit the form.
5. Repeat until all records are completed.

---

## ▶️ How to Run

1. Open the project in UiPath Studio.
2. Install required dependencies (if prompted).
3. Ensure browser extension is enabled.
4. Run `Main.xaml`.

---

## 🧠 Challenges Solved

* Handling dynamic UI elements where positions change after each submission.
* Reliable selectors using anchors instead of static positions.
* Maintaining performance while ensuring accuracy.

---

## 📸 Screenshots

(Add screenshots here)

---

## 👨‍💻 Author

Mohamed Sameh
Computer Science Student | RPA & Automation Enthusiast

---

## ⭐ Notes

This project was created for learning and demonstration purposes as part of RPA automation practice.
