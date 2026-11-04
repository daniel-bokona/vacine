





# Vaccine Tracker

A bilingual (English / Amharic) web app that helps families in Ethiopia keep track of vaccinations, even without an internet connection.

## 🎥 Video Presentation

[Watch the 5-minute demo (with voice-over)](https://drive.google.com/file/d/1hoe36d-wogDymW6hs-ZkgsBwGc0W90g_/view?usp=sharing)

## 📌 Project Description

This app generates a personalised vaccine schedule from a person's date of birth and sex, then tracks which doses are completed, upcoming, or overdue. Records are stored on the user's own device, and the app keeps working offline, which matters where connectivity is unreliable.

## 🎯 Purpose

Paper vaccine cards get lost, and many families don't know which vaccines are due next. This app gives caregivers and individuals one clear place to see what has been given, what is coming up, and what to do if a symptom appears after a dose.

## ✨ Main Features

- **Profile setup:** enter name, date of birth, and sex to generate a schedule automatically
- **Multiple profiles:** manage records for several family members and switch between them
- **Home dashboard:** upcoming, overdue, and completed vaccines at a glance
- **Dose logging:** record doses as they are given
- **Vaccine card and printable certificate:** an official-style card that can be printed
- **Vaccine catalog:** information about each vaccine
- **Nearby facilities:** a list of vaccination facilities (sample data in this prototype)
- **Symptom reporting and guidance:** log a symptom after a dose and get triage guidance on when to seek care, with a log history
- **QR code sharing:** show a QR code at a facility to share the record on file
- **Bilingual interface:** switch between English and Amharic (አማ)
- **Offline support:** shows a notice when offline and uses saved data
- **Privacy:** profile data stays on the device

## 🛠️ Tech Stack

- HTML5, CSS3, and vanilla JavaScript
- [qrcodejs](https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js) for QR code generation
- Google Fonts: Fraunces, Noto Sans, Noto Sans Ethiopic
- Data storage: browser/device storage only (no database)

## 🗄️ Data Storage

This project does **not** use a database integration. There is no backend or external database. All profile and vaccine data stays on the user's own device (in the browser), which is what lets the app work offline and keeps personal health information private. Facility listings are sample data built into the prototype.

## ⚙️ How to Run the Project

No installation is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
   cd REPO-NAME
   ```
2. Open `index.html` in your browser (or use a local server such as the VS Code "Live Server" extension).
3. Create a profile and start exploring.

## 📁 Project Structure

```
├── index.html   # App layout and screens
├── style.css    # Styling
├── app.js       # App logic (schedule, storage, language, QR, triage)
└── README.md
```

## 👥 Team Members

| No. | Full Name | CTC ID |
|-----|-----------|--------|
| 1   | Daniel Bokona | CTC-6112-26 |
